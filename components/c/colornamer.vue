<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><rect class="p2dngfbtc"/><rect class="f2mzh1bcv"/><path class="u41-8jbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:colornamer" /></template>
<style>
.f2mzh1bcv {
  width: 5.5px;
  height: 7.287px;
  x: 28.453px;
  y: 20.728px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.75px;
  ry: 2.75px;
}

.p2dngfbtc {
  width: 5.5px;
  height: 7.287px;
  x: 16.305px;
  y: 20.728px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.75px;
  ry: 2.75px;
}

.u41-8jbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.73 23.478a2.75 2.75 0 0 1 2.75-2.75m-2.751 0v7.288m-12.144-11v9.625c0 .759.616 1.375 1.375 1.375h.413M13.659 26.63a2.75 2.75 0 0 1-5.138-1.365v-1.787a2.75 2.75 0 0 1 5.135-1.37");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
