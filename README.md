# 搬瓦工购买流程：从选套餐、填优惠码到支付宝付款开通的完整步骤，新手也能一次下单成功

搬瓦工（BandwagonHost）的购买流程一共五步：选套餐、加购物车用优惠码、结账填资料、支付宝付款、查收邮件开通，顺利的话十来分钟就能走完。有两件事新手最容易卡住：一是搬瓦工没有独立的注册页面，账号在你第一次结账时自动创建；二是结账时 Country 必须选 China，否则支付方式里不会出现支付宝。下面按下单顺序把每一步拆开讲清楚，包括优惠码怎么填、哪些信息不能乱写、付款后去哪里找服务器信息。

> **选购速览**：大多数国内用户直接选 **CN2 GIA-E**（2 核 / 1GB 内存 / 20GB SSD / 1TB 月流量 / 2.5Gbps 带宽，季付 $49.99、年付 $169.99，可在 DC6、DC9、日本软银等十余个机房间免费切换）；只想低成本练手选 KVM（$49.99/年）。下单前记得 Country 选 China、优惠码点过验证再结账。👉 [查看 CN2 GIA-E 套餐当前价格](https://bwh81.net/aff.php?aff=77528&pid=87)

## 先搞清楚：搬瓦工没有单独的注册页面

搬瓦工把“注册”合并进了首次下单。你在结账页填写邮箱和密码，付款成功后账号即刻激活，VPS 同步开通，全程不需要单独去点什么 "Sign up"。

这个设计有个副作用：如果你按老习惯去找注册入口，大概率会卡在谷歌验证码上——验证码在国内网络环境下经常显示不出来，页面就一直过不去。正确的做法是从套餐购买链接进入下单流程，结账页右侧的 "New Customer" 表格就是注册表单。已经有账号的老用户在左侧登录即可，别重复建号。

## 第一步：选套餐，再决定付款周期

选套餐看两个问题：拿它做什么，以及对国内访问速度的要求有多高。预算极低、练手学 Linux，KVM 套餐 $49.99/年就够用；要建站或保证国内访问速度，直接看 CN2 GIA-E，2.5Gbps 带宽加三网优化线路，是绝大多数人该买的那个；对延迟极其敏感、预算也充足，再考虑香港和日本线路——它们贵不少，香港入门款标价 $89.99 但那是月付价，年付是 $899.99。

主流套餐整理如下：

| 套餐 | 核心配置（CPU/内存/硬盘/月流量/带宽） | 价格 | 购买 |
| --- | --- | --- | --- |
| KVM（入门） | 2核 / 1GB / 20GB SSD / 1TB / 1Gbps | $49.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&gid=1) |
| KVM 2GB | 3核 / 2GB / 40GB SSD / 2TB / 1Gbps | $52.99/半年 或 $99.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&gid=1) |
| CN2 GT | 1核 / 1GB / 20GB SSD / 1TB / 1Gbps | $49.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=57) |
| CN2 GIA LIMITED（限量） | 1核 / 1GB / 10GB SSD / 500GB / 1Gbps | $89.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=105) |
| CN2 GIA-E 1GB | 2核 / 1GB / 20GB SSD / 1TB / 2.5Gbps | $49.99/季 或 $169.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=87) |
| CN2 GIA-E 2GB | 3核 / 2GB / 40GB SSD / 2TB / 2.5Gbps | $89.99/季 或 $299.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=88) |
| 电商 SLA | 2核独享 / 1GB / 20GB SSD / 1TB / 2.5Gbps | $65.89/季 或 $239.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=164) |
| 日本大阪 | 2核 / 2GB / 40GB SSD / 500GB / 1.5Gbps | $49.99/月 或 $499.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&gid=1) |
| 日本大阪 | 4核 / 4GB / 80GB SSD / 1TB / 1.5Gbps | $86.99/月 或 $869.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&gid=1) |
| 香港 CN2 GIA | 2核 / 2GB / 40GB SSD / 500GB / 1Gbps | $89.99/月 或 $899.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=95) |

付款周期对总成本的影响比很多人以为的大，算笔账就清楚了：CN2 GIA-E 1GB 季付 $49.99，一年四季共 $199.96；年付一口价 $169.99，每年省 $29.97，相当于打了约 85 折。KVM 2GB 半年付两期共 $105.98，年付 $99.99，省 $5.99。香港套餐差距更夸张，月付 $89.99 跑满一年要 $1079.88，年付只要 $899.99，差了将近 $180。确定会用满一年，就直接选长周期。

下面是目前在售的其余高配套餐，普通个人用户基本用不到，列出来供对配置有硬需求的读者对照。其中 SLA 系列跑在 DC5 机房，官方承诺 99.99% 在线率，并且每两周可以免费更换一次 IP；CN2 GIA LIMITED 是限量款，10GB 硬盘加 500GB 月流量的配置偏小，官方专门设了补货通知群。

| 套餐 | 核心配置（CPU/内存/硬盘/月流量/带宽） | 年付价格 | 购买 |
| --- | --- | --- | --- |
| CN2 GT | 1核 / 2GB / 40GB / 2TB / 1Gbps | $99.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=58) |
| CN2 GT | 2核 / 4GB / 80GB / 3TB / 1Gbps | $199.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=59) |
| CN2 GT | 2核 / 8GB / 160GB / 5TB / 1Gbps | $399.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=67) |
| CN2 GT | 3核 / 16GB / 320GB / 8TB / 1Gbps | $799.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=68) |
| CN2 GT 大流量 | 3核 / 16GB / 320GB / 12TB / 1Gbps | $899.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=106) |
| CN2 GT 大流量 | 3核 / 16GB / 320GB / 16TB / 1Gbps | $1299.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=107) |
| CN2 GIA-E | 4核 / 4GB / 80GB / 3TB / 2.5Gbps | $549.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=89) |
| CN2 GIA-E | 6核 / 8GB / 160GB / 5TB / 5Gbps | $879.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=90) |
| CN2 GIA-E | 8核 / 16GB / 320GB / 8TB / 5Gbps | $1599.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=91) |
| CN2 GIA-E | 10核 / 32GB / 640GB / 10TB / 10Gbps | $2759.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=92) |
| CN2 GIA-E | 12核 / 64GB / 1280GB / 12TB / 10Gbps | $5499.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=93) |
| CN2 GIA-E 高CPU | 24核 / 64GB / 1280GB / 12TB / 10Gbps | $7599.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=148) |
| CN2 GIA-E 大流量 | 12核 / 64GB / 1280GB / 15TB / 10Gbps | $6790 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=160) |
| CN2 GIA-E 大流量 | 12核 / 64GB / 1280GB / 20TB / 10Gbps | $8999 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=161) |
| 电商 SLA | 3核独享 / 2GB / 40GB / 2TB / 2.5Gbps | $399.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=165) |
| 电商 SLA | 4核独享 / 4GB / 80GB / 3TB / 2.5Gbps | $699.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=166) |
| 电商 SLA | 6核独享 / 8GB / 160GB / 5TB / 5Gbps | $1099.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=167) |
| 电商 SLA | 8核独享 / 16GB / 320GB / 8TB / 5Gbps | $1999.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=168) |
| 电商 SLA | 10核独享 / 32GB / 640GB / 10TB / 10Gbps | $3699.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=169) |
| 电商 SLA | 12核独享 / 64GB / 1280GB / 12TB / 10Gbps | $6999.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=170) |
| 电商 SLA 大流量 | 12核独享 / 64GB / 1280GB / 15TB / 10Gbps | $8799.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=171) |
| 电商 SLA 大流量 | 12核独享 / 64GB / 1280GB / 20TB / 10Gbps | $11598.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=172) |
| 香港 CN2 GIA | 4核 / 4GB / 80GB / 1TB / 1Gbps | $1559.99（$155.99/月） | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=96) |
| 香港 CN2 GIA | 6核 / 8GB / 160GB / 2TB / 1Gbps | $2999.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=97) |
| 香港 CN2 GIA | 8核 / 16GB / 320GB / 4TB / 1Gbps | $5899.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=98) |
| 香港 CN2 GIA | 10核 / 32GB / 640GB / 6TB / 1Gbps | $9989.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=122) |
| 香港 CN2 GIA | 12核 / 64GB / 1280GB / 8TB / 1Gbps | $18989.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=124) |
| 日本 CN2 GIA | 2核 / 2GB / 40GB / 500GB / 1.2Gbps | $899.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=108) |
| 日本 CN2 GIA | 4核 / 4GB / 80GB / 1TB / 1.2Gbps | $1559.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=109) |
| 日本 CN2 GIA | 6核 / 8GB / 160GB / 2TB / 1.2Gbps | $2999.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=110) |
| 日本 CN2 GIA | 8核 / 16GB / 320GB / 4TB / 1.2Gbps | $5899.99 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=111) |

机房这件事不用在下单时纠结太久：购买页只能选该价位对应的机房，买完之后可以在 KiwiVM 面板里免费切换到套餐支持的任意机房，数据保留。CN2 GIA-E 的可选机房最多，香港套餐则覆盖香港、东京、大阪、新加坡等 15 个机房。套餐买小了也能付费升级，按当前需求下单就行。👉 [打开搬瓦工全部在售套餐页面](https://bwh81.net/aff.php?aff=77528&gid=1)

## 第二步：加入购物车并使用优惠码

优惠码在购物车页填写，位置在订单总览下方的 Promotional Code 输入框。填完必须点 Validate Code，右侧总价刷新变少才算生效，确认无误再点 Checkout 结账。

目前常用的两个循环折扣码：BWH3HYATVBJW（6.58%）和 BWHCGLUKKB（6.77%），填一个就行，互相不叠加。所谓“循环”，意思是续费时也按折扣价走，所以第一次买就填上，之后每个周期都在省。黑五、新年这类节点官方偶尔会放出力度更大的限时码，平常不用专门等。优惠码会不定期变动，最终以结账页验证通过的结果为准。

## 第三步：结账页填写资料，这一步就是注册

结账页同时完成注册和下单，最容易出错的字段是 Country，逐项过一遍：

- **Email Address**：用真实常用的邮箱。登录、接收服务器信息、找回密码全靠它。
- **Password**：设置包含大小写字母和数字的强密码。
- **Country**：必须选 China。选了别的国家，支付方式里不会出现支付宝选项，这是新手翻车率最高的一步。
- **State/Region、City、地址**：选 China 后按提示正常填写即可，不必精确到真实门牌号，但别用 "sdfsdf" 这类乱码——搬瓦工的欺诈检测会把无意义信息当成风险订单拒掉。
- **Payment Method**：国内用户选 Alipay，也支持银联、PayPal 和信用卡。
- 勾选 "I have read and agree to the Terms of Service"，点 Complete Order。

两个提醒：下单时不要挂代理或 VPN，注册 IP 和填写的国家对不上，订单容易被风控取消；资料填错了也不用慌，购买之后可以在后台修改。

到这一步信息都填对了，就可以放心提交订单了。👉 [用支付宝开通 CN2 GIA-E 套餐](https://bwh81.net/aff.php?aff=77528&pid=87)

## 第四步：确认账单并完成支付宝付款

点下 Complete Order 并不会马上扣款，系统先生成一张待支付账单。在账单页核对套餐名称和总金额，点付款按钮进入支付方式选择页。注意支付宝在这里还要再确认一次：点 "Pay … with Alipay"，页面才会跳到支付宝收银台。金额按当天实时汇率自动折算成人民币，收银台上直接显示，手机扫码或登录网页版支付宝付款都可以。银联、PayPal、信用卡用户的操作路径类似，在对应网关完成支付即可。

## 第五步：查收邮件，登录 KiwiVM 面板

付款成功后一两分钟，开通信息就会发到你的注册邮箱。重点是标题为 "KiwiVM Control Panel Details" 的那封，里面有 IP 地址、SSH 端口和 root 密码，三样凑齐才能连接服务器。特别提醒：搬瓦工的 SSH 端口是随机的五位数，默认不用 22，连不上服务器先检查端口填的是什么。邮件迟迟没到，翻一下垃圾邮件文件夹。

登录搬瓦工官网，进 Services → My Services，找到刚买的 VPS，点 KiwiVM Control Panel 进入管理面板。常用功能都集中在这里：开关机、重装系统（Debian、Ubuntu、CentOS 多个版本可选）、重置 root 密码、查看流量和 CPU 使用统计。

有两项功能值得单独记住。一是 Migrate to another DC，免费更换机房，不限次数，只消耗一次与硬盘容量等量的流量，数据全部保留，迁移前建议先做个快照兜底；二是快照功能免费，但最多保存两个永久版本，另外官方还提供免费的自动备份。安全方面，建议开通后第一件事就给面板开启两步验证（Two-factor authentication），KiwiVM 面板有独立密码，和账号密码分开设置更稳妥。

## 搬瓦工购买流程常见问题

### 搬瓦工怎么注册账号？

不需要单独注册。首次下单时在结账页填写邮箱和密码，付款成功后账号自动激活，VPS 同步开通。

### 搬瓦工支持支付宝吗？

支持。结账时 Country 选 China，支付方式里就会出现 Alipay 选项，此外还支持银联、PayPal 和国际信用卡。

### 优惠码填了没生效怎么办？

填入 Promotional Code 后必须点 Validate Code 才会刷新价格。优惠码不定期变动，验证通过以页面显示的实际折扣为准，两个码不要同时填。

### 付款后多久开通？

一般一两分钟内开通，服务器信息发送到注册邮箱。超过十分钟没收到，先检查垃圾邮件文件夹。

### 机房选错了怎么办？

在 KiwiVM 面板使用 Migrate to another DC 免费迁移，不限次数，数据保留，只消耗一次与硬盘容量等量的流量。

### 套餐买小了能升级吗？

可以付费升级到更高配置。机房则完全不用纠结，购买后随时可以免费切换。

## 按需求选套餐，下单前最后核对三件事

预算有限、想学 Linux 或跑点小项目，KVM 年付 $49.99 足够；要建站或保证国内访问速度，CN2 GIA-E 1GB 年付 $169.99，比季付每年省下约 $30；对延迟要求苛刻且预算充足，再看香港和日本线路，注意香港标价 $89.99 是月付价，别看错。如果你其实不想自己装环境、维护服务器，搬瓦工官方还有 Just My Socks 这类即买即用的服务，可以省去所有配置环节。

下单前最后核对三件事：Country 选了 China、优惠码点过 Validate Code、没有开代理。都没问题，就可以付款等邮件了。👉 [去搬瓦工挑选适合你的套餐](https://bwh81.net/aff.php?aff=77528&gid=1)
