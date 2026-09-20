<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eimgiyxfb"/><rect class="dwzs19bqq"/><path class="ivzd8dbbr"/><path class="n-57wvbyh"/><path class="a0i0-fbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duolingo-steaksaver-2" /></template>
<style>
.a0i0-fbhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.578 33.326a3.582 3.582 0 1 1-7.156 0M6.999 24.512l11.188 2.362v.927a5.594 5.594 0 0 1-11.188 0zm25.122.146a2.547 2.547 0 1 1 5.094 0v2.279a2.547 2.547 0 0 1-5.094 0z");
}

.dwzs19bqq {
  width: 11.188px;
  height: 14.476px;
  x: 29.813px;
  y: 18.918px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.594px;
  ry: 5.594px;
}

.eimgiyxfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.513 25.464v1.823a2.547 2.547 0 0 0 5.094 0v-.958");
}

.ivzd8dbbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.077 33.256A8.828 8.828 0 0 0 44.5 28.752v-5.19a8.8 8.8 0 0 0-2.21-5.844c0-1.926-.468-4.617-1.771-4.617s-2.509 1.945-2.509 1.945s.815-4.626-1.524-4.626c-3.327 0-5.084 8.956-12.485 8.956s-9.16-8.956-12.486-8.956c-2.34 0-1.524 4.626-1.524 4.626s-1.206-1.945-2.51-1.945s-1.77 2.691-1.77 4.617A8.8 8.8 0 0 0 3.5 23.562v5.19a8.83 8.83 0 0 0 8.828 8.828a8.82 8.82 0 0 0 7.595-4.324");
}

.n-57wvbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 33.833l4.9-.694a4.504 4.504 0 0 0-4.9-4.222a4.504 4.504 0 0 0-4.9 4.222z");
}

</style>
