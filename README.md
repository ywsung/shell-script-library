# shell-script-library

### 첫 번째 컬럼의 합 구하기
$ cat yesterday.log | awk '{ print $1 }'| paste -sd+ - | bc
