
#include <iostream>
Using namespace std;
Bool checkPrime(int numberToCheck)
{
if(numberToCheck == 1) {
return false;
}
for (int I = 2; i*I <= numberToCheck; i++) {
if (numberToCheck % I == 0) {
return false;
}
}
return true;
}
int primeSum(int l, int r)
{
int sum = 0;
for (int I = r; I >= l; i--) {
Bool isPrime = checkPrime(i);
if (isPrime) {
Sum = sum + I;
}
}
return sum;
}
int main()
{
int l = 4, r = 13;
Cout<<primeSum(l, r);
}
