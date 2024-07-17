public class Operator1 {
    public static void main(String[] args) {
        //변수 초기화
        int a = 5;
        int b = 2;

        //덧셈
        int sum = a + b;
        System.out.println("a + b = " + sum); //출력 a+b = 7

        //뺄셈
        int diff = a - b;
        System.out.println("a - b = " + diff); //출력 a-b = 3

        //곱셈
        int multi = a * b;
        System.out.println("a * b = " + multi); // 출력 a*b = 10

        //나눗셈
        int yw = a / b; //int형은 소숫점 표현 안됨
        System.out.println("a / b = " + yw); //출력 a/b = 2

        //나머지
        int mod = a % b;
        System.out.println("a % b = " + mod); // 나머지숫자 1만 남음
    }
}
