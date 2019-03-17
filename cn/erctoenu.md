[TOC]

# erc映射主网账户，使用imtoken

## 第一步

打开手机imtoken客户端，给enumivo映射地址将你的enu转到该地址上，其地址为：**0x8F58495479D3dddA44DeBC8cfE692B11F7bEFC6B**

图示:![erc1](.\erc1.jpg)

其旷工费的话根据自己的需求，打包速度快慢而已，自行决定。然后点击下一步等待转账成功。

## 第二步

等待转账成功后打开交易页面，复制交易url，获取txhash。如图所示：![erc3](.\erc3.jpg)

获取txhash之后，打开网页钱包映射界面，其地址是：https://wallet.enumivo.com/swap-token 将获得的txhash填入第二步。如图下所示：![erc4](.\erc4.jpg)

## 第三步

打开mew签名消息的网站，其网址是:https://vintage.myetherwallet.com/signmsg.html

在这里首先要将你的钱包导入到这个网站才能进行签名。

具体操作如图：![erc6](.\erc6.jpg)

**安全提醒：**请保证你的网络安全，确定你打开的是该网站，防止自己的私钥被盗窃！ps：图上私钥已做更改处理，属于无效私钥，纯作示例。

## 第四步

在解锁钱包之后，将你的txhash放入message 中，**并且将前两个字符ox**去除，如图所示:![erc7](.\erc7.png)

然后点击sign message 得到如下图所示：

![erc8](.\erc8.png)

sign 之后我们得到数据，将sig 中的数据进行复制回到映射界面

## 第五步

将sig的值填入step3 其结果如图所示：

![erc9](.\erc9.png)

到了这一步，接下来就是与主网相关的过程了。

## 第六步

1：如果你已经拥有主网账户，那么你只需要将你的主网账户填入，然后点击submit，界面会给你一个交易信息，你就可以去查看你的映射是否完成了。![erc11](.\erc11.png)

2:如果你目前还没有主网账户则还需要如下操作

* 首先在step4 选择 you want to creat an account 

* 在step5 中填入一个12位字符的用户名，**注意：**务必12位字符，否则无法创建成功

* step6中填入你的公钥(public key) 。公私钥的获取可以通过点击Get key Pair 来获取，如图所示：![erc12](.\erc12.png)

  获取之后将公钥填入其中即可。

* step7 中你需要进行enu ram的购买，目前买一个enu的ram即可。至此就完成了，点击Submit映射就完成了。填写信息实例如下：![erc14](.\erc14.png)

## 总结

这就是使用imtoken进行enu主网映射的教程，感谢社区成员提供的素材，有任何问题欢迎在微信，电报中提出，我们都会热心帮助每一个人。









