<p align="center">
    <img src="https://cdn.jsdelivr.net/gh/ruicky/ruicky.github.io/2020/06/05/jd-sign/0.png">
</p>

<p align="center">
    <img alt="Version" src="https://img.shields.io/badge/release-0.0.1-blue"/>
    <a href="https://github.com/ruicky">
        <img alt="Author" src="https://img.shields.io/badge/author-ruicky-blueviolet"/>
    </a>
</p>

# 京东自动签到
功能：
1. 获取签到最新代码
2. 替换参数值
3. 签到并发送通知

详情参考文章:[京东定时签到-GitHub 实现](https://ruicky.me/2020/06/05/jd-sign/) 


(要使用手机版或者触屏版)获得cookie方式:

var CV = '单引号里面放上面拿到的cookie';
var CookieValue = CV.match(/pt_pin=.+?;/) + CV.match(/pt_key=.+?;/);
copy(CookieValue);
console.log(CookieValue);


结果形如: pt_pin=XX;pt_key=XXXX;
(所以可以从cookie中直接拿值并自行拼接)
