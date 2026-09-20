<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uauri-b4n"/><circle class="dw6_1ybff"/><path class="lfe61iewg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iprint-and-scan" /></template>
<style>
.dw6_1ybff {
  cx: 18.154px;
  cy: 31.74px;
  r: 3.455px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lfe61iewg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.051 31.74h7.697m-7.697 2.362h4.963m-4.963-4.724h7.697");
}

.uauri-b4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.86 24.24v15h24.28v-15ZM7.5 8.76h33a3 3 0 0 1 3 3v2.058h-39V11.76a3 3 0 0 1 3-3m-3 5.058V27.6a3 3 0 0 0 3 3h4.36m24.28 0h4.36a3 3 0 0 0 3-3V13.818");
}

</style>
