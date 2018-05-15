#include<stdio.h>
void sum(int x)
{
  int j;

   for(j=1;j<=x;j++)
   printf("*");
  

}
int main()
{
  int repeat,m,n,i,j,p[180],k[6]={0};
  scanf("%d",&repeat);
  j=1;m=0;
  while(j<=repeat)
  {
      scanf("%d",&n);
      m+=n;
  for(i;i<m;i++)
  {
  scanf("%d",&p[i]);
  switch(p[i])
  {
    case 1:k[1]+=1;break;
    case 2:k[2]+=1;break;
    case 3:k[3]+=1;break;
    case 4:k[4]+=1;break;
    case 5:k[5]+=1;break;
  }
  }
  j++;}
  for (j=1;j<=repeat;j++;)
    for(i=1;i<=5;i++)
  {printf("%d:",i);
     sum(k[i]);
     printf("\n");}
     

  return 0;
}
