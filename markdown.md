# 标题

## 引用
> 位于河北张家口市的宣化古城是中国北方现存古城中历史悠久、规模宏大、地位重要的城池，为明长城“九镇之首”。自2005年开始，当地启动保护修复工程，目前已完成清远楼、时恩寺、高远门、角楼、马道等20多项保护修缮工程，7697米长的古城墙实现连通，初步恢复了古城“京师锁钥”的风貌。（新华社）

### 代码
```java
    static public boolean increaseLongVal(String key, Long ceiling)
    {
        lock(key);
        try{
        Long l = getLongVal(key);
        if(l==null)
            l=0L;
        if(ceiling==null || l.longValue()<ceiling.longValue())
        {
            l += 1L;
            setLongVal(key, l);
            return true;
        }
        else
            return false;
        }finally{unlock(key);}

    }
    
```

` if(ceiling==null || l.longValue()<ceiling.longValue()) `

-----------------------

#### 列表
- 这个fsafffsafd
dsfafdsdfs
- 那个
- 和

1. 这
1. 那
1. 和

##### 链接
所有的[活动](https://github.com/zr-soft/meaningful/blob/master/activity.json?raw=true "JSON" )都在此。
所有的[活动](/activity.json?raw=true)都在此。
所有的[活动][activity]都在此。

[activity]: https://github.com/zr-soft/meaningful/blob/master/activity.json?raw=true

- [x] 吃饭
- [ ] 睡觉
- [ ] 看电视


###### 表格

头一 | 头二 | 头三
-- | ------- | ----
1dfsssssssssssssssssssssssssssssssssss | 2 | 3


