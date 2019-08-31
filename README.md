# 一、标题的写法：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
# 二、表格写法
|格式字符|描述|示例|
|---|---|---|
|Y|四位数字的年份|2019|
|m|两位数字的月份|01-12|
|n|月份，1-9前面没有0前缀|1-12|
# 三、内容强调
* 1、*该部分为斜体*
* 2、**加粗部分**
* 3、***加粗且倾斜***
* 4、这是本句话`强调`的部分
# 四、代码块高亮
* 1、python代码高亮
```Python
def date_view(request):
    context = {
        "today": datetime.now()
    }
    return render(request, "date.html", context=context)
```
* 2、C代码高亮
```c
#include<stdio.h>
int main(void)
{
	int a = 10;
	printf("a");
	return a;
}
```
