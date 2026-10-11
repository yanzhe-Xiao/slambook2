## Slambook2
![titlepage](./figures/title.png)

Welcome to Slambook 2nd Edition! This is the codebase of our book. Here are some relavant links if you need them: 
- [Our book at jd.com](https://item.jd.com/12666058.html)
- [Our book at douban.com](https://book.douban.com/subject/27028215/) (I'll be happy to get a score at douban)
- [code of slambook version 1](https://github.com/gaoxiang12/slambook)
- [slambook in English](https://github.com/gaoxiang12/slambook-en) (Still on going)

Email me if you have any questions: gao.xiang.thu at gmail dot com. Or send a issue at github if your question is about the code.

Errata will be updated at this code base.

Hope you like this book.

BaiduYun backup link in case your github is very slow (common in China): [here](https://pan.baidu.com/s/1XQwpnDb3BOvxXZhL-03p3w)

### 📢 关于本 Fork 仓库的现代环境适配与第三方代码说明

本仓库为 [gaoxiang12/slambook2](https://github.com/gaoxiang12/slambook2) 的维护分支，主要适配现代 Linux 发行版（Ubuntu 22.04 / 24.04 / 26.04 等）与现代工具链（GCC 13/14/15、CMake 4.x、OpenCV 4、C++17 时代的 g2o / Ceres / PCL）。

#### 第三方库开源代码归属说明 (Third-Party Code Notice)
为了避免在新系统下拉取十年前上游子模块时因缺失 `<cstdint>` 等标头无法编译的问题，本仓库将以下第三方库直接作为代码目录内置管理并合入兼容性修复，版权与开源许可均属于原作者：
- **Pangolin** (`3rdparty/Pangolin`)：原作者 **Steven Lovegrove**，遵循 [MIT License](3rdparty/Pangolin/licence.txt)，原官方仓库为 [stevenlovegrove/Pangolin](https://github.com/stevenlovegrove/Pangolin)。已补充现代 GCC 严格模式所需的 `<cstdint>` 标头。
- **DBoW3** (`3rdparty/DBoW3`)：原作者 **Rafael Muñoz Salinas**，遵循 [BSD-3-Clause License](3rdparty/DBoW3/LICENSE.txt)，原官方仓库为 [rmsalinas/DBow3](https://github.com/rmsalinas/DBow3)。已补充现代 GCC 严格模式所需的 `<cstdint>`、`<iostream>`、`<string>` 与 `<cstddef>` 标头。

---
## 视觉SLAM十四讲：从理论到实践 第二版
欢迎来到视觉SLAM十四讲：从理论到实践。这里存放本书对应的代码文件。以下是一些可能对你有用的链接：
- [京东书籍链接](https://item.jd.com/12666058.html)
- [第一版书代码](https://github.com/gaoxiang12/slambook)
- [英文版代码](https://github.com/gaoxiang12/slambook-en) (正在翻译中)

如果您对书籍内容有疑问，请给我发送邮件。如果对代码有疑问，请点击上方的issue链接新建issues。我会不定期查看和回复（抱歉我可能无法回复所有问题和邮件）。

勘误表会更新到代码库中。

希望您喜欢本书。

本代码的百度云备份（如果您的github速度非常慢）[下载链接](https://pan.baidu.com/s/1XQwpnDb3BOvxXZhL-03p3w).
