## 数字

正数的正则表达式(包括 0，小数保留两位)<br>
export const PositiveFloat = /^((0{1}\.\d{1,2})|([1-9]\d*\.{1}\d{1,2})|([1-9]+\d*)|0)$/

正整数<br>
export const PositiveInteger = /^[+]{0,1}(\d+)$/

正数<br>
export const Positive = /^(0|[1-9][0-9]\*)(\.\d+)?$/

## 手机号

export const ExpTelephone = /^1[3456789]\d{9}$/
