# xiuxiu

* 什么是中间键？（来自于SOFAStack介绍）

* ERP（Enterprise Resource Planning）：企业资源计划
  + 建立在信息技术基础上，以系统化的管理思想，为企业决策层及员工提供决策运行手段的管理平台
  + 发展阶段：
    - MIS（Management Information System）
    - MRP（Material Require Planning）
    - MRP II（Manufacture Resource Planning）
    - ERP（Enterprise Resource Planning）
    - 电子商务时代的 ERP

* CI/CD
  - 持续集成(Continuous integration)
  - 持续部署（continuous deployment）

* DevOps（Development & Operations）
  + 代码管理（SCM）：GitHub、GitLab、BitBucket、SubVersion
  + 构建工具：Ant、Gradle、maven
  + 自动部署：Capistrano、CodeDeploy
  + 持续集成（CI）：Bamboo、Hudson、Jenkins
  + 配置管理：Ansible、Chef、Puppet、SaltStack、ScriptRock GuardRail
  + 容器：Docker、LXC、第三方厂商如AWS
  + 编排：Kubernetes、Core、Apache Mesos、DC/OS
  + 服务注册与发现：Zookeeper、etcd、Consul
  + 脚本语言：python、ruby、shell
  + 日志管理：ELK、Logentries
  + 系统监控：Datadog、Graphite、Icinga、Nagios
  + 性能监控：AppDynamics、New Relic、Splunk
  + 压力测试：JMeter、Blaze Meter、loader.io
  + 预警：PagerDuty、pingdom、厂商自带如AWS SNS
  + HTTP加速器：Varnish
  + 消息总线：ActiveMQ、SQS
  + 应用服务器：Tomcat、JBoss
  + Web服务器：Apache、Nginx、IIS
  + 数据库：MySQL、Oracle、PostgreSQL等关系型数据库；cassandra、mongoDB、redis等NoSQL数据库
  + 项目管理（PM）：Jira、Asana、Taiga、Trello、Basecamp、Pivotal Tracker
  
* 内存模型之缓存一致性 Cache coherence：https://www.cnblogs.com/jiayy/p/3246133.html
  + Intel 奔腾：MESI 协议
  + AMD opteron：MOESI 协议
  + Intel i7： MESIF 协议

* 并发编程：原子性问题，可见性问题，有序性问题https://www.cnblogs.com/dolphin0520/p/3920373.html
  + 原子性：一个操作或者多个操作 要么全部执行并且执行的过程不会被任何因素打断，要么就都不执行
  + 可見性：当多个线程访问同一个变量时，一个线程修改了这个变量的值，其他线程能够立即看得到修改的值
  + 有序性：程序执行的顺序按照代码的先后顺序执行
  + JAVA關鍵字：
    - synchronized和Lock：保證原子性、可见性、有序性
    - volatitle：只保證可見性、一定的“有序性”，不能保證原子性（当一个共享变量被volatile修饰时，它会保证修改的值会立即被更新到主存，当有其他线程需要读取时，它会去内存中读取新值）

  
  
