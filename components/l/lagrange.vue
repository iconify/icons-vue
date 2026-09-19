<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="renhmjb8c"/><circle class="l5hi7lzdi"/><ellipse transform="rotate(-30 21.743 25.301)" class="arro569xx"/><ellipse transform="rotate(-30 23.997 24)" class="r-i9f4n8h"/><path class="bqv18_7ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lagrange" /></template>
<style>
.arro569xx {
  cx: 21.743px;
  cy: 25.301px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.627px;
  ry: 18.708px;
}

.bqv18_7ju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.624 22.442c3.84 7.802 4.787 14.838 1.98 16.459c-3.17 1.83-9.926-3.94-15.092-12.889S13.726 8.327 16.896 6.497c2.684-1.55 7.943 2.353 12.629 9.02");
}

.l5hi7lzdi {
  cx: 36.069px;
  cy: 16.284px;
  r: 6.509px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r-i9f4n8h {
  cx: 23.997px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.627px;
  ry: 18.708px;
}

.renhmjb8c {
  cx: 15.455px;
  cy: 28.185px;
  r: 9.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
