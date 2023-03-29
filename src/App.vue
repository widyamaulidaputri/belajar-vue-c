><script setup xmlns="http://www.w3.org/1999/html">

</script>

<template>
  <h1><center>CAFE</center></h1>
  <center><img src="https://dcassetcdn.com/design_img/1430364/474889/474889_7277244_1430364_a5be26b3_image.jpg" alt="logo cafe"
  style="width: 100px;height: 100px;"/>
  </center>
  <h2><center>Login</center></h2>
  <form action="/action_page.php"><center>
    <label for="usname">Username:</label>
    <input type="text" id="username" name="username"><br><br>
    <label for="password">Pasworrd:</label>
    <input type="text" id="pass" name="pass"><br><br>
    <input type="submit" value="Submit"></center>
    <h3>Menu : </h3>
    <table >
      <tr>
        <th>Menu Makanan</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>Nasi Goreng</td>
        <td>25k</td>
      </tr>
      <tr>
        <td>Mie Goreng</td>
        <td>20k</td>
      </tr>
      <tr>
        <td>Mie Kwetiau</td>
        <td>20k</td>
      </tr>
      <tr>
        <td>Ayam Rica-Rica</td>
        <td>22k</td>
      </tr>

      <table>
          <th>Menu Minuman</th>
          <th>Price</th>
      <tr>
        <td>Air Mineral</td>
        <td>5k</td>
      </tr>
      <tr>
        <td>Teh Es</td>
        <td>6k</td>
      </tr>
      <tr>
        <td>Lemon Tea</td>
        <td>8k</td>
      </tr>
      <tr>
        <td>Jus</td>
        <td>10k</td>
      </tr>
        </table>
    </table><form action="/action_page.php"><label for="Menu"
    >Choose a Menu: </label>
      <select name ="Menu" id="Menu">
        <option value="Nasi Goreng">Nasi Goreng</option>
        <option value="Mie Goreng">Mie Goreng</option>
        <option value="Mie Kwetiau">Mie Kwetiau</option>
        <option value="Ayam Rica-Rica">Ayam Rica-Rica</option>
        <option value="Air Mineral">Air Mineral</option>
        <option value="Teh Es">Teh Es</option>
        <option value="Lemon Tea">Lemon Tea</option>
        <option value="Jus">Jus</option>

      </select>
      <br><br>
      <input type="submit" value="Submit"></form>
    </form>
  <form action="/action_page.php">

    <p><label for="Cafe"></label></p>
    <textarea id="Cafe" name="Cafe"
      rows="4" cols="20">Kritik dan Saran</textarea>
      </form>
    <p> Maps?Klik <a href="https://maps.app.goo.gl/ZGt2TErfAex6NZ6h7" >HERE!</a>
    </p>
  <h4> <center> Thank You </center> </h4>
</template>

<style scoped>


</style>
<style>
h5 {margin-left: 5px}
h6 {margin-top: 5px}
form {margin-top: 5px}
h3{color: #f8f3f3;}
body {
  background-image: url("https://tse3.mm.bing.net/th?id=OIP.1wfKalUpuDBatoNy5f8KnQHaE8&pid=Api&P=0");
  background-size: cover;}
table, th, td {border:2px solid #f8f3f3; color: aliceblue;}
form,p {color: aliceblue;}
h2 {color: #f8f3f3;}
</style>