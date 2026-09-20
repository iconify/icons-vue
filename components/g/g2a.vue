<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdqfr6dlj"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:g2a" /></template>
<style>
.hdqfr6dlj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.956 22.442a3.062 3.062 0 0 1 3.666-3c1.283.246 2.307 1.355 2.435 2.655c.095.967-.211 1.921-.879 2.508c-1.237 1.086-5.222 4.012-5.222 4.012h6.118m-8.457-6.175a3.059 3.059 0 1 0-6.117 0v3.116a3.059 3.059 0 1 0 6.117 0H15.56m18.927 0h-4.091m-1.013 3.059l3.058-9.234l3.059 9.234");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
