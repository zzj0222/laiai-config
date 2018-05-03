
直接查看配置文件中的配置信息可访问：http://localhost:9900/test-config-dev.properties

仓库中的配置文件会被转换成web接口，访问可以参照以下的规则：
/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
以neo-config-dev.properties为例子，它的application是neo-config，profile是dev。client会根据填写的参数来选择读取对应的配置。
