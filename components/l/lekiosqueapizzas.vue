<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqaikmy7v"/><ellipse class="jfnnbz86v"/><ellipse class="fqkk6bc1w"/><path class="lgebcxbii"/><path class="c87g2h1gg"/><path class="bg-dx_ytu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lekiosqueapizzas" /></template>
<style>
.bg-dx_ytu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.17 26.34V9.682c-9.202 0-16.62 7.436-16.62 16.66S13.968 43 23.17 43s16.69-7.436 16.69-16.66c0-2.359-.5-4.647-1.427-6.72z");
}

.c87g2h1gg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.45 14.938C38.882 9.075 33.033 5 26.257 5v16.66z");
}

.fqkk6bc1w {
  cx: 16.322px;
  cy: 21.836px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.068px;
  ry: 2.074px;
}

.jfnnbz86v {
  cx: 30.587px;
  cy: 30.059px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.996px;
  ry: 3.003px;
}

.lgebcxbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.459 36.851c2.354.715 4.779-.643 5.492-2.931M31.25 9.147c-1.141 2.145-.285 4.79 1.855 5.935");
}

.wqaikmy7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.46 27.127l-.285 5.935l-5.92-.358z");
}

</style>
