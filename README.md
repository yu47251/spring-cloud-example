# spring-cloud-example

## user-service
- 底层服务，模拟user服务，提供用户相关服务

## eureka-server
- Eureka的服务，

## caller
- 集成Feign，Ribbon，eureka-client，
- 完成服务发现，负载均衡，并且直接调用后端服务, 无网关.

## gateway
- 基于zuul，Feign，Ribbon，eureka的网关简单实现

## config-server
- 配置管理服务, 基于gitlab, security的配置管理服务

## demo
- 全是jar包，三个user-service，一个eureka-server，一个zuul网关,一个config-server
