<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="knnmf-jxb"/><circle class="pmk1z37tx"/><path class="grs03v_fq"/><circle class="gnmxz-onu"/><path class="iv94w3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ahamo" /></template>
<style>
.gnmxz-onu {
  cx: 13.434px;
  cy: 22.349px;
  r: 3.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.grs03v_fq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.691 22.349v3.125m-3.125-6.25s-1.742.103-2.524-1.256");
}

.iv94w3bar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.559 22.349v3.125m-3.125-6.25s-1.742.103-2.524-1.256m19.949 10.749c-1.415 2.007-4.03 3.243-6.859 3.243c-2.83 0-5.444-1.236-6.859-3.243");
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

.knnmf-jxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.652 16.041v9.433m0-3.891c0-1.302 1.051-2.358 2.348-2.358s2.348 1.055 2.348 2.358v3.891");
}

.pmk1z37tx {
  cx: 34.566px;
  cy: 22.349px;
  r: 3.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
