<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><rect class="zff1mybez"/><path class="mhjj3sb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:claro-flex" /></template>
<style>
.mhjj3sb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.142 26.15a2.1 2.1 0 0 1 2.101-2.101m-2.101 0v5.568m-8.097-8.405v8.405m6.108-2.101a2.101 2.101 0 0 1-4.202 0V26.15a2.101 2.101 0 0 1 4.202 0m-.001 3.467v-5.568m-8.084 2.749v.035a2.784 2.784 0 0 1-5.568 0v-2.837a2.784 2.784 0 0 1 5.568 0v.034m15.665-2.083v-3.564m3.168 4.941l3.152-3.152m-2.117 6.661H38.5m0 7.889l-3.499 4.637m3.499 0l-3.499-4.637m-1.276 3.754a1.75 1.75 0 0 1-3.27-.867v-1.137a1.75 1.75 0 1 1 3.5 0v.569h-3.5m-6.003-2.319h2.335m-1.412 4.638v-5.776c0-.677.548-1.225 1.225-1.225h.476c.603 0 .988.179 1.246.512v5.612c0 .483.392.875.875.875h.262");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.zff1mybez {
  width: 4.202px;
  height: 5.568px;
  x: 28.632px;
  y: 24.049px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.101px;
  ry: 2.101px;
}

</style>
