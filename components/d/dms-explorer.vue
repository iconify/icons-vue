<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="pa2aeb_dc"/><path class="vi7v9db5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dms-explorer" /></template>
<style>
.pa2aeb_dc {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.149px;
  ry: 16.149px;
}

.vi7v9db5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.529 26.445l-9.983 5.866c-2.036.738-3.4-.798-3.294-2.651V18.34c-.106-1.853 1.258-3.39 3.294-2.65l9.983 5.866c2.94 1.727 2.994 3.13 0 4.889");
}

</style>
