<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="e1axacb1h"/><rect class="rsgglkbtk"/><rect class="oqb_2f_ky"/><path class="hiwls6bjx"/><path class="bapwhtbgl"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lootboy" /></template>
<style>
.bapwhtbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.458 25.21v5.483a3.322 3.322 0 1 1-6.645 0V25.21");
}

.e1axacb1h {
  width: 6.645px;
  height: 8.804px;
  x: 20.645px;
  y: 25.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.322px;
  ry: 3.322px;
}

.hiwls6bjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.379 11.675v9.884c0 .917.744 1.66 1.661 1.66h.498m-3.903-8.804h3.488m-24.646 14.13a3.322 3.322 0 1 1 6.645 0v2.16a3.322 3.322 0 1 1-6.645 0m-.015 3.322V21.526m0-2.084V9.5m24.996 21.193v4.485a3.32 3.32 0 0 1-3.322 3.322a3.3 3.3 0 0 1-2.35-.973");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.oqb_2f_ky {
  width: 6.645px;
  height: 8.804px;
  x: 23.362px;
  y: 14.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.322px;
  ry: 3.322px;
}

.rsgglkbtk {
  width: 6.645px;
  height: 8.804px;
  x: 14.09px;
  y: 14.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.322px;
  ry: 3.322px;
}

</style>
