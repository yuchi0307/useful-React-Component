# useful React Component😘
方便重複使用的UI component
<ol>
  <li>Input</li>
  <li>Button</li>
  <li>Card</li>
</ol>
<br>
<h2>Input</h2>
<br>
<h2>Button</h2><br>

```
const Button = props => {

 return(
 <button
 type = {props.type || 'button'}
 classesName = {`${classes.button} ${props.className}`} //css module
 onClick = {props.onClick} //在父層使用該組件時把某 function 放入名為 onClick 的 attribute 中傳遞下來 
 disabled = {props.disabled}
 >
 {props.children}
 </button>
)
};

export default Button;
```

<br>
<h2>Card</h2>
