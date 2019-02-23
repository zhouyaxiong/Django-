# 介绍
世上一切的不幸都是由当事人能力不足引起的,
![千与千寻](https://tse2.mm.bing.net/th?id=OIP.Glfx0vY2PygLLTXOstSQKgHaEo&pid=Api)
>官网中文文档：http://docs.30c.org/djangobook2/chapter05/
## django属性
Django的MTV模式本质上与MVC模式没有什么差别
mvt框架的核心：解耦（出问题只修一个零件）。m代表数据库，因为老是变动，需要单独设置一个文件夹
Django 建造网站的基本途径： 建立视图（处理主管逻辑）和 URLConf
启动django就是启动socket服务端
django可以帮我们创建数据表，但是不能帮我们创建数据库

django的settings中指定了数据库的连接方式，install的app，静态文件(网站中的 js, css, 图片，视频)的位置static_url等


## 模板
django作为Web框架，Django提供了模板，可以很便利的动态生成HTML 模版系统致力于表达外观，而不是程序逻辑。

##项目开发流程：
1. 创建环境
2. 安装包
3. 创建项目,APP manage.py是启动文件
4. 在models.py 创建模型（关联数据库，创建数据表）生成迁移文件（只适应于关系型数据库）
5. 写Views接受请求，需要有return render_to_response
6. 配置URL完成数据操作
7. 创建模板，两个大括号中是变量
8. 运行项目，开发阶段提供了轻量级的web

