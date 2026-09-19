<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="out__z3xf"/><circle class="kcrhtubhr"/><circle class="r262w5bqa"/><path class="qjo9x_b_a"/><path class="po_2gqh3x"/><path class="j1-4mnlmj"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fabulous" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j1-4mnlmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.095 44.352l13.241-6.495h.01m13.978-6.858l-8.184 4.012m-9.228-.298H5.365");
}

.kcrhtubhr {
  cx: 36.378px;
  cy: 19.453px;
  r: 1.361px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.out__z3xf {
  cx: 29.652px;
  cy: 16.731px;
  r: 1.361px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.po_2gqh3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.355 41.038c.292-1.232 0-2.648 0-2.648m2.787 2.064c-.162-1.199-.602-2.62-.602-2.62M19.689 2.939a14.33 14.33 0 0 1 2.753 8.473c0 7.978-6.476 14.454-14.455 14.454c-1.941 0-3.78-.382-5.468-1.073");
}

.qjo9x_b_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.393 35.885c-.331-2.468-3.764-4.521-6.77-9.213a1.912 1.912 0 1 0-2.305-1.871c0 .751.437 1.395 1.068 1.707c-2.6 5.038-.749 10.304-1.846 12.65c6.029-2.885 5.607.194 9.853-3.273");
}

.r262w5bqa {
  cx: 35.017px;
  cy: 12.136px;
  r: 1.361px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
