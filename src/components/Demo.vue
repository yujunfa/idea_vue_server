<template>
  <div>
    <b-button @click="fun1" variant="primary">Hello</b-button>
  </div>
</template>

<script>
    export default {
        name: "",
        methods: {
            fun1() {
                confirm('Hello World!');
            }
        }
    }
</script>

<style scoped>

</style>
