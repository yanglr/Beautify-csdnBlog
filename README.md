# Beautify-csdnBlog
csdn博客公告栏美化指南...



目前定制处，代码行数有限制，iframe、embed、object等已不支持~



支持的标签：

`span`、`strong`、`table`、`a`、`marquee`、`font`等基本的



代码如下:
```html
<center><font face="隶书" color="red">
        <marquee direction="up" behavior="alternate" width="20" height="40">B</marquee><font color="#ff8900">
        <marquee direction="up" behavior="alternate" width="20" height="30">r</marquee><font color="#92c000">
        <marquee direction="up" behavior="alternate" width="20" height="40">a</marquee><font color="#00c024">
        <marquee direction="up" behavior="alternate" width="20" height="30">v</marquee><font color="#00c0da">
        <marquee direction="up" behavior="alternate" width="20" height="40">o</marquee><font color="#00c0da">
        <marquee direction="up" behavior="alternate" width="20" height="40">公</marquee><font color="#0053ff">
        <marquee direction="up" behavior="alternate" width="20" height="30">告</marquee><font color="#4800ff">
        <marquee direction="up" behavior="alternate" width="20" height="40">栏</marquee></font></font></font></font></font></font></font></font></font></center>
        
<table bgcolor='#F6F8FA'>
    <tr>
        <font color="blue">
            <strong>About me:</strong>
        </font>
    </tr>
    <tr align='left'>
        <br>
        <a target="_blank" href="https://yanglr.github.io">Blog - Github page</a>
        <br>

        <a href="http://stackoverflow.com/users/6075331/bravo-young" target="_blank">
            <strong>StackOverflow</strong>
        </a>
        <font>(</font>
        <img src="http://images.cnblogs.com/cnblogs_com/enjoy233/1389971/o_reputation-rp.png">
        <span>446 <font size=4 color=black>⬆</font>)</span>
    </tr>
    <div align="left">
<a href="https://stackexchange.com/users/4637854/bravo-yeung" target="_blank"><img src="https://stackexchange.com/users/flair/4637854.png" width="208" height="58" alt="profile for Bravo Yeung on Stack Exchange, a network of free, community-driven Q&A sites" title="profile for Bravo Yeung on Stack Exchange, a network of free, community-driven Q&A sites"></a>
    </div>
</table>
<table width="270px" bgcolor='#F6F8FA'>
    <tr valign="middle" align="left" bgcolor='#F6F8FA'>
        <th width='40px'>
            <a href="https://www.zhihu.com/people/legege007" title="知乎撩我" target="_blank">
                <img src="http://images.cnblogs.com/cnblogs_com/enjoy233/1389971/o_zhihu-dog.jpg" class="mr5" height='35'>
            </a>
        </th>
        <th valign='middle'>
            <font>(</font>
            <img src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_vote.png" width='15' height='15' title="赞同">
            42.8k <font size=4 color=black></font>
            <img src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_fav.png" width='15' height='15' title="收藏">
            90.7k <font size=4 color=black></font>
            <img src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_thank.png" width='15' height='15' title="感谢">
            21.7k <font size=4 color=black></font>)
        </th>
    </tr>
</table>
<table width="270px" bgcolor='#F6F8FA'>
    <tr bgcolor='#F6F8FA'>
        <a href="mailto:legege007@126.com?subject=测试发邮件&body=就是一个测试邮件">
            <strong>邮我</strong>
        </a>
        <br>
        <a href="https://segmentfault.com/blog/legege007" target="_blank">SegmentFault(SF)</a>
        <br>
        <marquee>
            <a href="#"><font color="blue" size="4">You will make it!
        </marquee>
        <br>
        <div align=center>
            <a href="https://www.cnblogs.com/enjoy233/" target="_blank">
                <img src="https://img-blog.csdnimg.cn/20190130021405714.gif">
            </a>
        </div>
        <div class="c-social" align="center">
            <a href="https://github.com/yanglr" target="_blank">
                <img width='60' height='60' src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_github.png">
            </a>
            <a href="https://www.zhihu.com/people/legege007" title="知乎撩我" target="_blank">
                <img width='60' height='60' src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_zhihu.png">
            </a>
            <a href="https://www.cnblogs.com/enjoy233/" title="我在博客园" target="_blank">
                <img width='60' height='60' src="http://images.cnblogs.com/cnblogs_com/enjoy233/1389971/o_cnblog_logo.png">
            </a>
            <a href="http://weibo.com/546671991" target="_blank">
                <img width='60' height='60' src="https://www.cnblogs.com/images/cnblogs_com/enjoy233/1389971/o_weibo.png">
            </a>
        </div>
        <br>
<strong>友链:</strong>
        <br>
        <a href="http://www.fogsail.net" target="_blank">Fogsail Chen</a>
        <br>
        <a href="http://tinylab.org/" target="_blank">吴章金falcon@TinyLab</a>
        <br>
  </tr>
</table>
```


**效果如下:**

![csdn公告栏效果](https://cdn.jsdelivr.net/gh/yanglr/Beautify-csdnBlog/images/csdn-show.gif)
