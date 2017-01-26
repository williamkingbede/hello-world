# hello-world
<!DOCTYPE html>
<html lang = ″en″>
 <head> 
  <title> Exercise 2 </title>
  <meta charset = ″utf-8″ />
  <script type="text/javaScript" src="Exercise2.js"></script>
 </head>
 <body>
  <h1> Order Books Online</h1>
  <div>
  <table>
   <tr>
    <td><strong>Book</strong></td>
    <td><strong>Quantity</strong></td>
    <td><strong>Price</strong></td>
   </tr>
   <tr>
    <td>Basic XHTML</td>
    <td><form><input type="text" id="XHTML" size="5" required></input></form></td>
    <td>$19.99</td>
   </tr>
   <tr>
    <td>Intro to PHP</td>
    <td><form><input type="text" id="PHP" size="5" required><form/></input></td>
    <td>$86.00</td>
   </tr>
   <tr>
    <td>Advanced JQuery</td>
    <td><form><input type="text" id="JQ" size="5" required></input></form></td>
    <td>$55.00</td>
  </table><br/><br/>
  <button onclick="total()">Place Order</button>
  </div>
  <p id="demo">
  </p>
 </body>
</html>