### 구현 결과
https://github.com/user-attachments/assets/aa44bf68-0eff-4921-b659-fcbcb70a0e94

### **요구사항**

### **요구사항**

- [x]  사용자가 입력한 문자열 값에 따라 사칙연산을 수행할 수 있는 계산기를 구현해야 한다.
    
    예를 들어 "2 + 3 x 4 / 2"와 같은 문자열을 입력할 경우 2 + 3 x 4 / 2 실행 결과인 8을 출력해야 한다.
    
- [x]  **사칙 연산의 우선순위를 적용한다. (`x` , `/` 는 1순위, `+` ,`-` 는 2순위)**

- [x]  [**피그마**](https://www.figma.com/design/PUwKOQ98OulmCcWqJLkkvf/%EA%B3%BC%EC%A0%9C-%EB%AA%A9%EB%A1%9D?node-id=1-3&t=2BXcqg02LGA3iIJA-4)에 맞춰 화면을 구현하면 됩니다.
    - [x]  키패드에서 숫자를 입력하거나 `=` 나, `-`, `/` , `*`를 입력하면 동작할 수 있어야 합니다.``
- [x]  테스트 케이스 딱 하나 작성하기.
    - [x]  사칙연산 우선순위가 잘 나오는지 확인하기.
    - [x]  `2 + 3 x 4 / 2 = 8` 이거 딱 하나만 테스트 코드에 넣어주세요.
    
### 예시

```sql
"2 + 3 x 4 / 2"와 같은 문자열을 입력할 경우 2 + 3 x 4 / 2 실행 결과인 8을 출력해야 한다.
```