<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="l8xnx4b-o"/><path class="zcjuq5bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:itslearning" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.l8xnx4b-o {
  cx: 14.413px;
  cy: 14.88px;
  r: 0.75px;
  fill: currentColor;
}

.zcjuq5bil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.413 18.913V31.87m11.574-1.093c.892.75 1.856 1.093 4.02 1.093h1.098a3.236 3.236 0 0 0 3.232-3.239h0a3.236 3.236 0 0 0-3.232-3.24H28.91a3.236 3.236 0 0 1-3.232-3.238h0a3.236 3.236 0 0 1 3.232-3.24h1.097c2.164 0 3.128.344 4.02 1.094M20.068 14.88v14.545a2.445 2.445 0 0 0 2.444 2.445h.734m-5.745-12.957h5.133");
}

</style>
