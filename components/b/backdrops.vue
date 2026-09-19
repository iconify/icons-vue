<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="xfb7v_7wu"/><path class="h_ej-bb9z"/><path class="i-p5nrb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:backdrops" /></template>
<style>
.h_ej-bb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.304 13.248h5.562a1.235 1.235 0 0 1 1.237 1.238v19.027a1.235 1.235 0 0 1-1.237 1.238h-5.43m-17.06 0h-5.241a1.235 1.235 0 0 1-1.238-1.238V14.486a1.235 1.235 0 0 1 1.237-1.238h5.563");
}

.i-p5nrb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.103 16.384h3.16a1.235 1.235 0 0 1 1.237 1.238v12.755a1.235 1.235 0 0 1-1.237 1.238h-3.16m-30.207 0H5.737A1.235 1.235 0 0 1 4.5 30.377V17.622a1.235 1.235 0 0 1 1.237-1.238h3.16");
}

.xfb7v_7wu {
  width: 16.608px;
  height: 31.707px;
  x: 15.696px;
  y: 8.147px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.238px;
}

</style>
