<template>
  <div class="hello">
    <h1>{{ awal }}</h1>
    <b> {{ nama }} <br> {{ npm }} </b>
    <p>
     Ini adalah halaman pertama saya menggunakan framework Vue.js, dan pertama kali menggunakan framework frontend.
    </p>
    <h3>Kunjungi website saya</h3>
    <ul>
      <li><a href="https://afrizalmy.com" target="_blank" rel="noopener">Web Portofolio</a></li>
      <li><a href="https://blog.afrizalmy.com" target="_blank" rel="noopener">Web Blogsite</a></li>
    </ul>
    <h3>Harapan</h3>
    <p>
      Semoga saya bisa memahami dan mengembang projek dengan Vue.js
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  data () {
    return {
      awal: 'Selamat datang di Vue.js App',
      nama: 'Afrizal Muhammad Yasin',
      npm: '17081010092'
    }
  },
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
