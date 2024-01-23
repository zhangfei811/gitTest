
<template>
  <div class="test-one"></div>
</template>
<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>
<style scoped lang="less">
.test-one {
  width: 100vw;
  height: 100vh;
  background: #000;
}
</style>
