<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q35lgzb0c"/><circle class="ir4p5iebm"/><path class="xwr7pj74p"/><rect class="tc-bbj-es"/><path class="uyhyw2bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:automate" /></template>
<style>
.ir4p5iebm {
  cx: 24.47px;
  cy: 14.76px;
  r: 2.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q35lgzb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.17 15.82l9.45-.04l-9.65 4.83l-1.5-3.84m0-4.02l1.5-3.84l9.65 4.82l-9.45-.03M12.4 23.84a3.53 3.53 0 0 1-3.52 3.52a3.52 3.52 0 1 1 3.52-3.52m21.41 1.35a2.89 2.89 0 0 1 1-2.38a1.77 1.77 0 0 1 2.19-.07a2.89 2.89 0 0 1 1.14 2.32m-13.25.13a2.9 2.9 0 0 1 1-2.38a1.77 1.77 0 0 1 2.15-.07a3 3 0 0 1 1.14 2.32m8.31 3.85a6.34 6.34 0 0 1-3 5.45a5.76 5.76 0 0 1-6 0a6.34 6.34 0 0 1-3-5.45m-5.05 1.35a4.4 4.4 0 1 0 0 8.79");
}

.tc-bbj-es {
  width: 22.2px;
  height: 39px;
  x: 20.44px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.uyhyw2bxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.16 9.5h15.48m-22.2 29h22.2m-16.9-29h-5.3");
}

.xwr7pj74p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.46 26.22l5.77 5.43m5.32-16.29l-10.87 6.36");
}

</style>
