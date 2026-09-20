<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><rect class="zff1mybez"/><path class="jd4ebjxue"/><rect class="u_ft8s9qb"/><circle class="ugq4k69cl"/><path class="moa5qabsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:claro-video" /></template>
<style>
.jd4ebjxue {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.142 26.15a2.1 2.1 0 0 1 2.101-2.101m-2.101 0v5.568m-8.097-8.405v8.405m6.108-2.101a2.101 2.101 0 0 1-4.202 0V26.15a2.101 2.101 0 0 1 4.202 0m-.001 3.467v-5.568m-8.084 2.749v.035a2.784 2.784 0 0 1-5.568 0v-2.837a2.784 2.784 0 0 1 5.568 0v.034m15.665-2.083v-3.564m3.168 4.941l3.152-3.152m-2.117 6.661H38.5m-16.548 8.136l-1.657 4.39l-1.656-4.39");
}

.moa5qabsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.609 34.969v4.39m9.431-.836a1.657 1.657 0 0 1-3.096-.82v-1.078a1.657 1.657 0 0 1 3.314 0v.539h-3.314m-1.5-.539a1.657 1.657 0 0 0-3.314 0v1.077a1.657 1.657 0 1 0 3.314 0m0 1.657v-6.627");
}

.u_ft8s9qb {
  width: 3.314px;
  height: 4.391px;
  x: 34.864px;
  y: 34.969px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.657px;
  ry: 1.657px;
}

.ugq4k69cl {
  cx: 23.609px;
  cy: 32.939px;
  r: 0.75px;
  fill: currentColor;
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
