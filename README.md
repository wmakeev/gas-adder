# gas-adder

> [AdderScript](http://adderscript.com/) for GAS

## Usage

```js
AdderScript.init()

const compiledCode = AdderScript.compile(`
a = 1
b = 3
a + b`)

const program = AdderScript.newProgram(compiledCode)

program.execute()

const lastVal = program.getLastValue()

console.log(lastVal) // 4
```
