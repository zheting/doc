# 分布式系统开发实战篇 - TCC分布式事务实现



## 什么是事务

![image-20210123071401274](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123071401274.png)

## 事务的特性

![image-20210123071729594](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123071729594.png)

## 事务例子

![image-20210123071932685](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123071932685.png)

![image-20210123072048844](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072048844.png) 

![image-20210123072159379](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072159379.png)

## 原子性和一致性

![image-20210123072331140](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072331140.png)

## 隔离性

![image-20210123072427326](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072427326.png)

### 脏读

![image-20210123072513899](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072513899.png)

### 不可重复读

![image-20210123072939653](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123072939653.png)

### 虚读

![image-20210123073133775](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123073133775.png)



## MySQL隔离级别

![image-20210123073328627](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123073328627.png)



## 分布式事务

### 什么是分布式事务

![image-20210123073716764](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123073716764.png)

### 分布式事务理论

#### CAP

![image-20210123073925210](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123073925210.png)

![image-20210123074023554](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123074023554.png)

![image-20210123074258653](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123074258653.png)

#### BASE理论

![image-20210123074527756](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123074527756.png)

![image-20210123074625759](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123074625759.png)

![image-20210123074820154](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123074820154.png)



## 分布式事务协议

![image-20210123075150146](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123075150146.png)



## 分布式事务解决方案

 ![image-20210123075859921](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123075859921.png)



## TCC 补偿事务

**T**ry  **C**onfirm  **C**ancel

![image-20210123080004604](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123080004604.png)



![image-20210123080626946](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123080626946.png)

 ![image-20210123081154534](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123081154534.png)

类似spring retry

![image-20210123082134167](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123082134167.png)



 ![image-20210123082536128](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123082536128.png)



![image-20210123083008608](分布式系统开发实战篇 - TCC分布式事务实现.assets/image-20210123083008608.png)











