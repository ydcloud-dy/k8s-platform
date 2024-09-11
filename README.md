# k8s-platform
=======
# k8s多集群管理平台

### 1、基本介绍 

多集群资源管理平台，基于管理k8s的资源开发，可以管理k8s的namespace、Deployment、Daemonset、StatefulSet、Service、Ingress、Pods、Nodes、CronJob、Velero等，并且支持终端等功能。

**功能详细说明**：

1. K8S原生资源管理，多集群管理，提供表单资源管理，YAML方式管理，终端管理等能力。
2. 平台 用户与Kubernetes RBAC打通，提供个人凭据申请，集群用户管理，集群用户授权，集群权限管理能力。
3. 阿里云开源控制器Openkruise管理能力。
4. 集成Prometheus 监控能力（未完成）。
5. 集成CloudTTY 能力。(CloudTTY 是专为 Kubernetes 云原生环境打造的 Web 终端和 Cloud Shell Operator。 通过 CloudTTY，操控多云资源。）
6. NodeShell 能力。
=======
8. NodeShell 能力。
7. 提供多云资产管理功能，目前包括阿里云、腾讯云、华为云，主要包括云上负载均衡、云服务器、云数据库。
8. 提供本地资产管理，可根据项目隔离主机，批量导入主机（未完成）

方便运维对Kubernetes集群资源的细粒度授权，方便开发管理Kubernetes内的应用对其进行故障排查，提供友好的操作页面降低使用复杂性。

### 2、技术栈

该项目前后端分离，前端vue3、后端使用golang开发

涉及技术栈有：

1、gin：web框架

2、gorm：orm库

3、CasBin：访问控制中间件

4、client-go：k8s api客户端

### 3、项目部署

