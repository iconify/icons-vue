<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="orc3-8lhe"/><circle class="r8nfp-b6x"/><circle class="t3yrrobbg"/><path class="k0brt33xn"/><circle class="z__de5b2f"/><circle class="ko7q6sbyd"/><path class="w4r1tgzai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:awful" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k0brt33xn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.918 19.297v-.799");
}

.ko7q6sbyd {
  cx: 34.993px;
  cy: 14.881px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.orc3-8lhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.55 25.34c6.48-1.26 13.76-1.96 21.45-1.96s14.97.7 21.45 1.96m-24.368-6.043v-.799");
}

.r8nfp-b6x {
  cx: 13.007px;
  cy: 14.881px;
  r: 4.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t3yrrobbg {
  cx: 13.007px;
  cy: 14.881px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w4r1tgzai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.344 12.78c-1.066-1.96-3.763-4.58-7.351-5.028S29.967 10.95 24 10.95s-7.405-3.644-10.993-3.197s-6.285 3.067-7.35 5.028");
}

.z__de5b2f {
  cx: 34.993px;
  cy: 14.881px;
  r: 4.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
