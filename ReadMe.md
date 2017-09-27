## 介绍

支持跨库连表，条件复合筛选，PK缓存查询等

同步异步请求分离，类的自动化加载管理

支持Form表单验证，支持事件触发机制

具有sql防注入，html防xss等特性

高性能，框架响应时间在1ms以内，单机tps轻松上3000

GitHub 地址：[https://github.com/Tencent/Biny](https://github.com/Tencent/Biny)

## 使用文档

#[http://www.billge.cc](http://www.billge.cc)

## FAQ

Q: 框架跟传统PHP框架区别在哪儿，有什么优势？

A: Biny是个自由度很高的框架，不像其他框架需要配置各种路由，自动加载类，复杂的命名空间。这些在Biny中都是不需要的，按照一个简单的规则就能快速使用这些功能。从开发者的角度出发，在功能上使用非常简单。而且具有相当强的安全性。从框架层面完全屏蔽了 SQL注入和 XSS注入两大安全难题，非常适合新人使用。

Q: Biny框架的性能如何？

A: 测试机：Intel Xeon Processor E5506 (4M Cache, 2.13 GHz, 4.80 GT/s Intel？ QPI)
一个普通查询数据页面（50%命中缓存）QPS 能轻松达到3000以上，同比Yii，性能是Yii的2倍以上。

Q: 我想使用Biny，请问有相关说明文档吗？

A: 文档都在[http://www.billge.cc](http://www.billge.cc)中，有问题也欢迎RTX交流

Q: Biny框架适配PHP7吗？

A: 可以完美运行，性能提高2倍以上。

Q: Biny现在是最终版了吗，还会继续更新吗？

A: 目前版本在多个项目中已经正常使用，相对成熟。后续会针对性能和功能上都会持续更新，届时只需更新替换 lib库 即可使用最新框架。