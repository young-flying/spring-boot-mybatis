该项目为spring boot 集成mybatis

坑：
1.引入mybatis-spring-boot-starter jar包时要注意版本号
我是用的是1.3以上的版本，该版本要匹配spring Boot1.5 or higher ,我用的是spring Boot1.4，这个坑了我好久
启动就是加载不了mybatis配置 
error: Cannot load configuration class: org.mybatis.spring.boot.autoconfigure.MybatisAutoConfiguration



启动：
启动类 ：org.jewi.work下的Application