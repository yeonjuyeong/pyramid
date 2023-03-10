# pyramid

```java
import java.util.Scanner;
public class Sungil21110_Test07 {

	static void spira(int n){
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=n-i;j++)
				System.out.print(" ");
			for(int j=1;j<=(i-1)*2+1;j++)
				System.out.print("O");
			System.out.println();
		}
	}
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner sc = new Scanner(System.in);
		int n;
		
		System.out.println("피라미드를 출력합니다.");
		
		do {
			System.out.println("단수는: ");
			n = sc.nextInt();
		}while (n <=0);
		spira(n);
	}

}
```
####매개변수를 사용하여 for문 돌리기
```java
	static void spira(int n){
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=n-i;j++)
				System.out.print(" ");
			for(int j=1;j<=(i-1)*2+1;j++)
				System.out.print("O");
			System.out.println();
      ```
 #### 스캐너로 값을 입력받고 do while문으로 0이하의 숫자를 걸러내기
	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner sc = new Scanner(System.in);
		int n;
		
		System.out.println("피라미드를 출력합니다.");
    
    		do {
			System.out.println("단수는: ");
			n = sc.nextInt();
		}while (n <=0);
		spira(n);
	}
