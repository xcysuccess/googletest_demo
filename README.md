##### Mac OS下安装测试gtest
[https://www.jianshu.com/p/68b9d2682cdd](https://www.jianshu.com/p/68b9d2682cdd)

```objc
git clone https://github.com/google/googletest.git
```

brew gcc新版

```objc
https://wangxin1248.github.io/life/2019/06/mac-update-gcc.html
brew search gcc
brew install gcc@8
sudo vi ~/.bash_profile
alias gcc='gcc-8’
alias cc='gcc-8’
alias g++='g++-8’
alias c++='c++-8’
source ~/.bash_profile
```

[https://my.oschina.net/u/4287712/blog/3629897](https://my.oschina.net/u/4287712/blog/3629897)

```objc
更改
vim ../CMakeLists.txt
添加
set(CMAKE_CXX_STANDARD 11)
```

##### C++ 项目之Googletest单元测试

[https://cloud.tencent.com/developer/article/1510229](https://cloud.tencent.com/developer/article/1510229)