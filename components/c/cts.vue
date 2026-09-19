<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kz2yubbhl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cts" /></template>
<style>
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

.kz2yubbhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.47 17.874a5.97 5.97 0 1 0 5.155 8.986M18.2 15.272h12.169m-6.085 12.566V15.272m8.075 12.566h1.649v4.89h-3.981zm3.411 1.081c1.87-.134 2.73-.967 2.73-2.445c0-3.014-6.482-1.82-6.482-5.46c0-2.387 3.923-3.24 6.482-1.25");
}

</style>
