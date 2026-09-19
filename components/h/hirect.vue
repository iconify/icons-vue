<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yo43fuw7d"/><path class="uja57pb_d"/><circle class="w4jrgxbwx"/><path class="f2clhoeyd"/><circle class="too2hdpdd"/><path class="yvym4abvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hirect" /></template>
<style>
.f2clhoeyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.825 17.546l-1.724 13.038m6.931-7.974H17.16");
}

.too2hdpdd {
  cx: 32.035px;
  cy: 19.228px;
  r: 2.514px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uja57pb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 44.569h18.488a1.743 1.743 0 0 0 1.602-2.432l-2.739-6.372");
}

.w4jrgxbwx {
  cx: 18.399px;
  cy: 12.554px;
  r: 2.514px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yo43fuw7d {
  cx: 24px;
  cy: 23.069px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvym4abvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.46 24.22l-1.724 13.037m.862-7.973h-5.872");
}

</style>
