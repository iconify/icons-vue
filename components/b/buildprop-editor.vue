<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="hv4asgb7d"/><path class="b dv3zvdygq"/><ellipse class="gfh38x77c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buildprop-editor" /></template>
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

.dv3zvdygq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.043 22.944a3.244 3.244 0 0 1 3.211-3.256m-3.211 0v8.629m-9.212-3.257a3.212 3.212 0 1 0 6.423 0v-2.116a3.212 3.212 0 1 0-6.423 0m0-3.256v13.025m23.915-7.653a3.212 3.212 0 1 0 6.423 0v-2.116a3.212 3.212 0 1 0-6.423 0m-.001-3.256v13.025");
}

.gfh38x77c {
  cx: 7.446px;
  cy: 32.459px;
  fill: currentColor;
  rx: 0.74px;
  ry: 0.75px;
}

.hv4asgb7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.736 28.315a3.244 3.244 0 0 1-3.211-3.256v-2.117a3.212 3.212 0 1 1 6.423 0v2.117a3.244 3.244 0 0 1-3.212 3.256");
}

</style>
