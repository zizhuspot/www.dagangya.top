---
title: 隐蔽数十年！全球数据通信技术TETRA揭秘惊人后门
date: 2023-07-28 14:18:00
categories:
  - 信息安全
tags:
  - 渗透测试
  - 间谍
  - 网络安全
description: 2023年爆出了一个史诗级的漏洞/后门曝光事件！据报道，这个漏洞或后门存在了长达几十年的时间，而且据信美国可能一直在利用它来进行全球监听
cover: https://s2.loli.net/2023/07/28/cb2rQIxPXwEOYfz.png
---
![image.png](https://s2.loli.net/2023/07/28/St8VZiQGjTLnx2J.png)

2023年爆出了一个史诗级的漏洞/后门曝光事件！据报道，这个漏洞或后门存在了长达几十年的时间，而且据信美国可能一直在利用它来进行全球监听。

该漏洞或后门被指是一种高度隐秘的技术手段，允许黑客或者国家间谍机构在未经授权的情况下远程访问和控制计算机系统、网络设备或其他智能设备。这样的漏洞可能导致用户的隐私和安全受到严重威胁，同时也可能被滥用来进行大规模的全球监听和监视。

这个曝光事件引起了广泛的关注和担忧，因为它揭示了现代通信和网络技术中的一个重大安全漏洞。许多专家和用户对于这样的漏洞存在的时间之久以及其可能造成的后果感到震惊和愤怒。

政府和科技公司被指责没有及时发现和修复这个漏洞，同时也引发了公众对于隐私和数据安全的担忧。对于这一事件的调查和解决办法仍在进行中，但是对于全球范围内的数据安全和隐私保护问题，已经成为一个紧迫的议题。

## 三名荷兰安全研究人员揭示TETRA欧洲无线电标准漏洞

自上世纪90年代以来，TETRA标准在无线电通信中广泛使用，涵盖摩托罗拉、达姆、海特拉等公司的设备。然而，由于其使用的加密算法一直保密，这些漏洞可能长期未被察觉。

Ampere工业安全公司的顾问Caleb Mathis指出，尽管美国并未广泛采用TETRA标准，但据文件显示美国至少有二十多个关键基础设施采用了基于TETRA的无线电设备。同时，由于TETRA内嵌于PowerTrunk等系统集成商提供的无线电设备中，目前难以准确定位厂商使用TETRA标准的情况。Mathis确认美国一家州边境控制机构、一家炼油厂、化工厂、东海岸的一家大型公共交通系统、三家国际机场用于安保和地勤人员通信，以及一家美国陆军训练基地使用了TETRA标准。

2021年，荷兰Midnight Blue公司的Carlo Meijer、Wouter Bokslag和Jos Wetzels发现TETRA存在漏洞（被称为TETRA:Burst），并同意在无线电制造商公开缓解措施和打补丁之前不公开披露漏洞信息。

随后，荷兰国家网络安全中心（Dutch National Cyber Security Centre，NCSC）负责通报漏洞问题，并协调研究人员在公开披露问题的时间框架。NCSC发言人Miral Scheffer表示TETRA对荷兰和全球关键通信至关重要，因此通信设备必须始终保持安全可靠。

通告中，Miral Scheffer确认TETRA漏洞可能允许受影响无线电附近的网络攻击者“拦截、操纵或干扰”通信，并指出荷兰国家通信安全委员会已通知德国、丹麦、比利时和英国等国，建议严肃对待此事。

美国国土安全部网络安全和基础设施安全局的发言人表示已察觉到TETRA漏洞，但不愿发表更多评论。

TETRA漏洞带来的潜在危害巨大，研究人员再次强调任何使用无线电技术的组织都应立即与制造商联系，确认其设备是否使用了TETRA标准，并了解可用的修复或缓解措施。此外，研究人员计划在下个月的拉斯维加斯BlackHat安全会议上披露详细的技术分析和尚未公开的秘密TETRA加密算法，希望其他拥有更多专业知识的组织和个人能够深入研究这些算法。

## 美英等国或已经利用 TETRA 漏洞窃取信息

针对研究人员发现的TETRA标准中的问题，Murgatroyd指出ETSI在去年10月发布的TETRA标准修订版中已修复了密钥流和时间戳问题，并且创建了另外三种供应商可用的算法，其中一种取代了TEA1。供应商已经提供了修复密钥流和时间戳问题的固件更新，但对于TEA1的问题，目前唯一的解决办法是使用另一种算法。

然而，Wetzels指出，供应商的操作面临一些挑战，因为加密必须应用于每台设备，造成了高昂的成本，并且升级需要停机时间，这对于关键基础设施来说显然非常困难，甚至可能导致与其他组件不兼容的问题。此外，要求供应商换用新的算法取代TEA1也面临困难，因为ETSI计划将这些算法和其他算法一样保密，并要求用户再次相信这些算法没有关键弱点。

目前，研究人员尚不清楚他们发现的漏洞是否被积极利用，但他们在爱德华·斯诺登披露的信息中发现了漏洞被利用的证据，这意味着美国国家安全局（NSA）和英国GCHQ情报机构过去曾将TETRA作为窃听目标。

另一份文件还显示，美国国家安全局（NSA）和澳大利亚信号局（Australian Signals Directorate）在2007年巴厘岛气候变化会议期间窃听了马来西亚警方的通信，并获得了一些关于印尼安全部队TETRA通信的收集信息。此外，斯诺登泄密的文件还描述了2010年英国政府通信总部（GCHQ）可能在美国国家安全局（NSA）的协助下，在阿根廷收集TETRA通信信息，当时阿根廷与英国因福克兰群岛（Falkland Islands）海岸外深海油田的石油勘探权问题关系紧张。

## 关于 TETRA

上世纪 90 年代，欧洲电信标准协会（ETSI）开发了 TETRA 标准，该标准包括 TEA1、TEA2、TEA3 和 TEA4 四种加密算法，无线电制造商可根据产品的预期用途和客户，在不同的产品中使用这些算法。

TEA1 用于商业用途，但根据 ETSI 文件显示，对于欧洲和世界其它地区关键基础设施中使用的无线电来说，TEA1 也是为公共安全机构和军队设计的，研究人员发现警察机构也在使用它；TEA2 在欧洲被警察、应急服务、军事和情报机构限制使用；TEA3 可用于欧洲以外被视为对欧盟“友好”国家的警察和紧急服务，例如墨西哥和印度等国；研究人员表示，商业算法 TEA4 几乎不被使用。

需要指出的是，研究人员在进行开源研究后发现除美国外，全球绝大多数警察部队都使用基于 TETRA 的无线电技术。据不完全统计，包括比利时，塞尔维亚、摩尔多瓦、保加利亚和马其顿等东欧国家以及中东的伊朗、伊拉克、黎巴嫩和叙利亚等国的警察部队、保加利亚、哈萨克斯坦和叙利亚的国防部、波兰军事反情报机构、芬兰国防军、黎巴嫩和沙特阿拉伯情报部门等也在使用它。美国和部分国家的关键基础设施在 SCADA 和其他工业控制系统设置中使用 TETRA 进行机器对机器通信，尤其是在广泛分布的管道、铁路和电网中（这些地方可能无法使用有线和蜂窝通信）。

值得注意的是，虽然 TETRA 该标准本身可以公开审查，但加密算法只有在签署保密协议的情况下才能提供给受信任的各方，如无线电制造商。供应商必须在其产品中包含保护措施，以使任何人都难以提取算法并对其进行分析。为了获得这些算法，研究人员购买了一台摩托罗拉 MTM5400 无线电设备，花了四个月从无线电固件的安全包中找到并提取算法。

研究过程中，研究人员不得不使用一些零日漏洞来破解摩托罗拉的保护措施，（漏洞上报给了摩托罗拉进行修复。研究人员表示所有四种 TETRA 加密算法都使用 80 位密钥，即使在发布二十多年后，仍能提供足够的安全性，防止有人破解，但 TEA1 有一个功能，可以将密钥减少到 32 位，不到密钥长度的一半。在进行逆向工程算法后，研究人员发现的第一个漏洞是 TEA1 中的后门，研究人员使用一台标准笔记本电脑和四个密码文本，不到一分钟就破解了它。

负责 TETRA 标准的 ETSI 技术机构主席 Brian Murgatroyd 反对将此漏洞称为后门。Brian Murgatroyd 指出在制定标准时，需要一种能满足出口要求的商业用途算法，以便在欧洲以外地区使用。1995 年时，32 位密钥仍能提供安全性，但以今天的计算能力，32 位密钥的安全性可能不太能够应对当前的网络威胁形式。

约翰-霍普金斯大学密码学家兼教授马修-格林（Matthew Green）称削弱的密钥无疑是一场 “灾难”。德国波鸿鲁尔大学（Ruhr University Bochum）计算机科学教授兼安全研究团队 CASA 的密码学家 Gregor Leander 更是指出在没有添加端到端加密的情况下，关键基础设施使用 TEA1 是愚蠢行为。对于外界的评论，Murgatroyd 坚称 TETRA 具有强大的身份验证功能，可以防止注入虚假通信，任何人利用该后门最多只能对数据和通话进行解密和窃听。

Wetzels 强调 TETRA 仅要求设备向网络验证自身身份，但无线电之间的数据和语音通信不需要数字签名或以其它方式进行身份验证。无线电和基站相信任何具有正确加密密钥的设备都经过身份验证，因此可以像研究人员那样破解密钥的人可以用它加密自己的消息并将其发送到基站和其他无线电。

虽然 TEA1 的"弱点"一直不为公众所知，但它在业界和政府中显然是广为人知。在 2006 年泄露给维基解密的美国国务院电报中，美国驻罗马大使馆表示一家意大利无线电制造商询问向伊朗市政警察部队出口TETRA 无线电系统的问题，美国曾反对该计划，因此该公司代表提醒美国，其计划出售给伊朗的基于 TETRA 无线电系统中加密“小于40位”，这就意味着该系统没有使用强密钥，美国不应该反对出售。

研究人员发现的第二个漏洞并不存在于某个秘密算法中，但仍旧能够影响所有算法。当 TETRA 无线电设备与基站联系时，它们通过时间同步启动通信。网络广播时间，无线电则确定时间同步，然后两者生成与时间戳相关联的相同密钥流，对随后的通信进行加密。

Wetzels  表示网络以未经验证和加密的数据包形式广播时间，因此网络攻击者可以使用一个简单的设备拦截和收集无线电与基站之间的加密通信，同时记下启动通信的时间戳。然后就可以利用一个恶意基站与同一无线电或同一网络中的不同无线电联系，并广播与被拦截通信相关联时间相匹配的时间戳。无线电是没有”判断能力的“，它认为正确的时间就是基站所广播的时间。因此，无线电会生成当时用于加密攻击者收集到的通信密钥流。攻击者在恢复该密钥流后，就可以用它来解密之前收集到的通信。

整个过程中，为了注入虚假信息，网络攻击者可以利用基站告诉无线电时间是明天中午，并要求无线电生成与未来时间相关的密钥流，一旦攻击者得到密钥流，就可以使用密钥流加密自己的虚假信息，并在第二天中午使用该时间的正确密钥流向目标无线电发送信息。

但是 ETSI 的 Murgatroyd 淡化了这种攻击，称 TETRA 的强认证要求可以防止未经认证的基站注入信息，对于这一说法，Wetzels 很是反对并指出 TETRA 只要求设备对网络进行认证，而不是相互认证。

研究人员在欧洲警方、军方和紧急服务部门使用的 TEA2 算法中没有发现任何弱点，但最开始认为在 TEA3 中发现另一个后门，再加上 TEA3  是 TEA2 的可出口版本，有充分理由怀疑它也可能有后门，以满足出口要求。

研究人员表示在算法中使用的 S-box 中发现了可疑之处，该 S-box 包含一种其认为 "绝不会出现在严肃的密码学中 "的不良属性。研究人员没有足够的技术来检查它，以确定它是否可被利用。但 Leander 的团队确实对其进行了检查并表示事实并非如此。

Leander 指出在许多密码中，如果使用 S-box  这样一个盒子，就会严重破坏密码，但在 TEA3 中的使用方式，看不出留给了攻击者的可乘之机。此外，Leander 表示虽然这并不意味着其他人不会发现其中的蛛丝马迹，但如果 S-box 能导致一种实用的攻击，自己会感到非常惊讶。
