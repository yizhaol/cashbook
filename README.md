# 原作者文档站
- 官方文档站：[https://doc.cashbook.oldmoon.top](https://doc.cashbook.oldmoon.top)
- 在线体验：[cashbook.oldmoon.top](https://cashbook.oldmoon.top/) (体验账号: `cashbook`/`cashbook`)
- 在线体验后台：[cashbook.oldmoon.top/admin](https://cashbook.oldmoon.top/admin) (体验账号: `admin`/`admin123456`)

## 简述（Description）

Cashbook记账本。

- 在数据记录上追求简单、易用、自主可控；
- 在统计分析上力求清晰、美观、简洁有效。

## 方法：
1. 配置数据库
2. 拉取github项目后修改docker-compose.yml为自己的配置参数运行docker-compose.yml
> 最基本的前台启动（用于调试，Ctrl+C 可停止）

>docker-compose up

>更常用的方式：后台启动（守护进程模式)

>docker-compose up -d
