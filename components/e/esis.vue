<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4fovi9ld"/><circle class="t0m74_5yy"/><path class="hfxy5pbcj"/><path class="g4f4yla7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esis" /></template>
<style>
.g4f4yla7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.5 16.21A6.91 6.91 0 0 0 23 28.32l-.32 3.47L26 29.85a6.6 6.6 0 0 0 1.5.15a6.91 6.91 0 0 0 0-13.82Z");
}

.hfxy5pbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.14 21.93l1.36-.29v5.76l1.37-.3");
}

.t0m74_5yy {
  cx: 27.5px;
  cy: 19.12px;
  r: 0.75px;
  fill: currentColor;
}

.w4fovi9ld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 28.22h5.31M4.5 17.6h5.31M4.5 22.91h3.46M4.5 17.6v10.62m7.24-1.17a3 3 0 0 0 2.6 1.17h1.57a2.66 2.66 0 0 0 2.65-2.66h0a2.65 2.65 0 0 0-2.65-2.65h-1.74a2.65 2.65 0 0 1-2.64-2.65h0a2.65 2.65 0 0 1 2.64-2.66h1.57a3 3 0 0 1 2.61 1.17m18.33 8.28a3 3 0 0 0 2.6 1.17h1.57a2.66 2.66 0 0 0 2.65-2.66h0a2.65 2.65 0 0 0-2.65-2.65h-1.73a2.65 2.65 0 0 1-2.65-2.65h0a2.65 2.65 0 0 1 2.65-2.66h1.57a3 3 0 0 1 2.6 1.17");
}

</style>
