<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jenl1baqb"/><circle class="m209e9job"/><circle class="gn1bkubvc"/><circle class="ofa6u1btq"/><path class="t2-0mbb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ball2box" /></template>
<style>
.gn1bkubvc {
  cx: 23.794px;
  cy: 35.925px;
  r: 1.155px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jenl1baqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.7 25.08l-1.734 3.003V43.5h20.068V28.083l-1.668-3.002zm-1.734 3.003h20.068");
}

.m209e9job {
  cx: 23.87px;
  cy: 35.88px;
  r: 5.264px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ofa6u1btq {
  cx: 21.78px;
  cy: 17.881px;
  r: 4.496px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t2-0mbb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.44 9.31l1.415 4.718m-.361-7.98l1.898 6.654m-.32-8.202l2.039 7.38m.162-6.549l1.778 6.25m.748-4.511l1.314 4.92");
}

</style>
