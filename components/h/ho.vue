<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="yees3ibtb"/><path class="m8lvorbao"/><circle class="xt1ntfb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ho" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.m8lvorbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 24.801V38.5m0-5.65a3.425 3.425 0 1 1 6.85 0v5.65");
}

.xt1ntfb6d {
  cx: 29.009px;
  cy: 38.255px;
  r: 0.75px;
  fill: currentColor;
}

.yees3ibtb {
  width: 6.85px;
  height: 9.076px;
  x: 19.65px;
  y: 29.424px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.425px;
  ry: 3.425px;
}

</style>
