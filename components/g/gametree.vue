<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yc6p95bka"/><circle class="gfuwl_ttn"/><circle class="vfy8r4bis"/><circle class="kgut3vj6p"/><path class="r4gi2f2tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gametree" /></template>
<style>
.gfuwl_ttn {
  cx: 15.608px;
  cy: 21.167px;
  r: 4.344px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kgut3vj6p {
  cx: 34.911px;
  cy: 23.273px;
  r: 1.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r4gi2f2tu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.608 23.493v-4.652m-2.326 2.326h4.652");
}

.vfy8r4bis {
  cx: 31.005px;
  cy: 19.287px;
  r: 1.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc6p95bka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.015 28.193c7.065.072 8.62 10.644 16.174 7.604c6.367-2.563 1.899-14.056.18-17.828c-2.073-4.551-5.423-6.123-8.083-6.15c-3.18-.032-5.347 2.73-8.132 2.702s-4.896-2.834-8.075-2.867c-2.66-.027-6.042 1.476-8.207 5.985c-1.795 3.736-6.495 15.137-.181 17.828c7.49 3.193 9.259-7.345 16.324-7.274");
}

</style>
