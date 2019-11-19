# EasyLogin

EasyLogin is a login module, build with ARouter. You can use it to free up your time！



It just like use a LoginActivity. So before you enjoy it please implematention Alibaba/ARouter first. 



Add this in your app/gradle

```java
// ARouter
implementation 'com.alibaba:arouter-api:1.5.0'
```



Good! And then please add my repository to your project, like this:



```java
compile('com.fishinwater:login:1.0')
```



At last, add this to project/gradle:



```java
allprojects {
    repositories {
        ...
        maven { url "https://github.com/yuanhao-1999/EasyLogin/raw/master" }
        ...
        
    }
}
```

