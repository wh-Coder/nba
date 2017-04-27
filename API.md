- 赛事日历
```
url: http://sportsnba.qq.com/match/listByDate
param:  data 日期
        [appver]
        [appvid]
        [network]
eg: http://sportsnba.qq.com/match/listByDate?date=2017-04-27&appver=1.0.2.2&appvid=1.0.2.2&network=wifi
    http://sportsnba.qq.com/match/listByDate?date=2017-04-27
```

- 战绩榜

```
url: http://sportsnba.qq.com/team/rank
param: [appver]
       [appvid]
       [network]
eg: http://sportsnba.qq.com/team/rank?appver=1.0.2.2&appvid=1.0.2.2&network=wifi
    http://sportsnba.qq.com/team/rank
```

- 虎扑

```
url: http://bbs.mobileapi.hupu.com/1/7.0.8/forums/getForumsInfoList
param: sign
       password
       stamp
       token
       client
       fid
       night
       lastTid
       isHome
       type
       special
       limit
eg: http://bbs.mobileapi.hupu.com/1/7.0.8/forums/getForumsInfoList?sign=6a1614f2baa444a5b81c329f2a446d30&password=0&stamp=&token=&client=863583024643703&fid=44&night=0&lastTid=&isHome=1&type=1&special=0&limit=20
```

- 详细帖子
```
url: http://bbs.mobileapi.hupu.com/1/7.0.8/threads/getThreadDetailInfoH5
param: tid
eg: http://bbs.mobileapi.hupu.com/1/7.0.8/threads/getThreadDetailInfoH5?tid=19066971
```
