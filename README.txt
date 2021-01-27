# how_to_decide_int_ornot




#include<stdio.h>
#include<math.h>
int main()
{
//    double a=0.999999999;
    double a=0.99999999999999999999999999999999999999999999999999999999999;

    if       (floor(a + 0.5) == a)
    {
        printf("%s","yes是整数");
    }
    else
    {
        printf("%s","no不是整数");
    }
    return 0;
}

