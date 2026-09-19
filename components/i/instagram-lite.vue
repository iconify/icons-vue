<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="setjl4m9q"/><circle class="j5chwv-8z"/><circle class="iugic1b2k"/><circle class="upxwd5bwx"/><path class="w1i_ubcyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instagram-lite" /></template>
<style>
.iugic1b2k {
  cx: 22.5px;
  cy: 22.5px;
  r: 8.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j5chwv-8z {
  cx: 33.85px;
  cy: 11.15px;
  r: 2.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.setjl4m9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 4C5.784 4 4 5.784 4 8v29c0 2.216 1.784 4 4 4h23.272A7 7 0 0 1 30 37a7 7 0 0 1 11-5.742V8c0-2.216-1.784-4-4-4z");
}

.upxwd5bwx {
  cx: 37px;
  cy: 37px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w1i_ubcyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 33v8h4");
}

</style>
