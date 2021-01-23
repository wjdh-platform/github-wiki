# github-wiki
关于git和github使用的手册整理
### 添加hosts中的ip映射

> 整理时间：2020年12月25日07:23:47最新整理

> 解决问题：无法查看github上面的图片和视频、github访问速度太慢

- 解决方案1：使用管理员身份编辑hosts文件（文件位置C:\Windows\System32\drivers\etc\hosts）在host文件中末尾粘贴下列ip-网址映射

- 解决方案2：由于github的ip会出现变动，所以授人以鱼不如授人以渔，下面教大家如何更新github的ip映射

1.访问<https://www.ipaddress.com>

![ip主页](/enter-ipaddress.png)

2.查询ip,比如输入github.com，点击搜索（放大镜）

![页面](/get-ipi.png)

3.使用管理员身份编辑hosts文件（文件位置C:\Windows\System32\drivers\etc\hosts）

4.修改相应url的ip地址

```

# GitHub Start
#2021年1月22日21:50:57 
140.82.112.3      github.com
140.82.112.3      gist.github.com

#2021年1月22日21:51:06
185.199.108.153    assets-cdn.github.com
185.199.109.153    assets-cdn.github.com
185.199.110.153    assets-cdn.github.com
185.199.111.153    assets-cdn.github.com

#2021年1月22日21:51:13
199.232.96.133    raw.githubusercontent.com
199.232.96.133    gist.githubusercontent.com
199.232.96.133    cloud.githubusercontent.com
199.232.96.133    camo.githubusercontent.com

#2021年1月22日21:50:48
185.199.108.154   github.githubassets.com
185.199.109.154		github.githubassets.com
185.199.110.154		github.githubassets.com
185.199.111.154		github.githubassets.com

#2021年1月22日21:51:26
199.232.96.133    avatars0.githubusercontent.com
199.232.28.133    avatars1.githubusercontent.com
199.232.96.133    avatars2.githubusercontent.com
199.232.96.133    avatars3.githubusercontent.com
199.232.96.133    avatars4.githubusercontent.com
199.232.96.133    avatars5.githubusercontent.com
199.232.96.133    avatars6.githubusercontent.com
199.232.96.133    avatars7.githubusercontent.com
199.232.96.133    avatars8.githubusercontent.com
199.232.96.133 	  avatars.githubusercontent.com

#2021年1月22日21:51:40
199.232.96.133    githubusercontent.com user-images.githubusercontent.com
140.82.112.5	 	  api.github.com
3.218.144.29  		collector.githubapp.com
3.224.212.168 		collector.githubapp.com
54.146.190.157		collector.githubapp.com
199.232.69.194		github.global.ssl.fastly.net
# GitHub End
```

### Chrome浏览器查看github网站时安装的插件

#### 1.octotree

>url:https://www.octotree.io/

Octotree是一个 Chrome插件，用来显示 Github 项目的目录结构。主要针对于广大的程序猿童鞋们，Github上面成千上万的开源项目给程序猿带来很多帮助，还可以学习大神们的思想，向大神看齐。不过，在Github上查看源代码的体验十分糟糕，尤其是从一个目录跳转到另一个目录的时候，非常麻烦。octotree插件就能很好地解决了上述问题。安装之后，浏览托管在Github上的项目，可看到左侧的树形结构，更方便查看代码，给你一种LDE般的体验感。

## 解析ip地址使用https://www.ipaddress.com/
