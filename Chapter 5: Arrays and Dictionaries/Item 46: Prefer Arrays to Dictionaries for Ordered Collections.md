# 條款 46 優先選用陣列來建立有序群集而非使用字典

**戡誤**

Item 46
    Page 123, code example: The argument to report() is an array identical to in the "correct" version on the next page. The text around the example suggests that the argument should have been an object. The intention was probably along the lines of: (reported by Stein Magnus Jodal)

```javascript
report({ Hank: 1110100,
        Steve: 1064500,
        Billy: 1050200 });
```

- 要順序，選 []
- 不要順序，選 {}
