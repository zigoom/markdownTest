
### 8. 이미지 넣기
[여름](https://github.com/zigoom/markdownTest/blob/main/abc.jpeg)

### 7. 하이퍼 링크
[PCWK](https://cafe.daum.net/pcwk)


### 6. 가로선
화면 전체를 가로지르는 가로선  : -,*을 3개 이상
---
***
---

### 5. 목록
#### 하위목록
1.  아이템1  
1.  아이템2  
  1.1.  1단계 하위 아이템  
    1.1.1.  2단계 하위 아이템  

#### 무순서 목록
* 목록이름
- 목록이름
+ 목록이름 

#### 순선있는 목록
1. 목록이름
1. 목록이름
1. 목록이름



### 4. 코드블럭
```python
def main():

    count = int(input("구매 상품 수를 입력 하세요?"))
    totalPrice = 0 #총금액

    for num in range(1,count+1):
        price = 1000
        print("2+1 상품입니다.")

        if (num % 3 == 0):
            pass
        else:
            totalPrice += price

    print("총 가격은 {}원 입니다.".format(totalPrice))

main()
```

### 3. 인용상자
> 여기에 인용할내용을 넣으면 됩니다.  
> 빈 줄이 없으면 자동으로 인용 상자에 포함 됩니다.  
식사 맛나게 하셨나요

인용이 끝났습니다.  


### 2. 헤더
'''#을 1개부터 6개까지 6단계로 사용할수 있습니다.'''
# Java
## Html
### CSS
#### Javascript
##### JSP
###### Spring



### 1. 문단 구분을 위한 개행
여름 공원을 걸어 보아요.  
(개행 :space 2개)
여름을 만끽 하세요.
