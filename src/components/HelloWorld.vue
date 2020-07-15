<template>
  <div class="hello">
    <button @click="count++">按钮：{{count}}</button>
  </div>
</template>

<script>
import { reactive } from 'vue';

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  setup () {
    const count = reactive({
      count: 1
    })
    return {
      ...state
    }
  }
}
</script>

<style scoped>
</style>
