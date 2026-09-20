<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7_y3kwag"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gotham-sports" /></template>
<style>
.d7_y3kwag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.918 30.269c1.018 1.22 2.239 1.831 4.07 1.831h2.442a4.08 4.08 0 0 0 4.07-4.07a4.08 4.08 0 0 0-4.07-4.07h-2.645a4.08 4.08 0 0 1-4.07-4.07a4.08 4.08 0 0 1 4.07-4.07h2.442c1.831 0 3.052.407 4.07 1.832M22.54 21.345a5.497 5.497 0 0 0-5.52-5.52a5.497 5.497 0 0 0-5.52 5.52v5.52c0 3.066 2.453 5.315 5.52 5.315s5.52-2.453 5.52-5.315h-5.52");
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
