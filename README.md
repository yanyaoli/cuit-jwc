# 易通知

📣 易通知 成都信息工程大学教务处每日通知推送

每日监测教务处新通知并进行推送，利用 `pushplus` 实现推送功能。

<img src="./intro/simple.jpg" height="400">

> [!TIP]
>
> 群组二维码，微信扫码加入群发群组，每天获取教务处通知。
>
> <img src="https://etz.cuit.workers.dev/qr" height="300">


## 使用方法

1. [克隆本仓库](https://github.com/yanyaoli/etz/fork)

2. 选择自己的分支仓库 -> `Settings` -> `Secrets and Variables` -> `Action` -> `New repository secret`，添加以下内容：
- - [x] **TOKEN**, 必填项, [官网](https://pushplus.hxtrip.com/)免费申请
- - [ ] TOPIC, 如果需要群发，可以设置群组ID
