<template>
  <div class="hello">
    <h3>{{ msg }}</h3>
    
    <form action="/dashboard">
      <label for="email">Email:</label>
      <input type="text" placeholder="Your email address..." name="email">
      <br>
      <label for="password">Password:</label>
      <input type="text" placeholder="Your password..." name="password">
      <br>
      <button type="sumbit">Login</button>
    </form>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
