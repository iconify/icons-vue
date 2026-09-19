<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4wilq-dr"/><circle class="nsu31v9da"/><circle class="rg-cc_x3n"/><circle class="w1b8kbsfz"/><path class="tdtjefb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:listmyapps" /></template>
<style>
.nsu31v9da {
  cx: 11.018px;
  cy: 12.892px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rg-cc_x3n {
  cx: 10.701px;
  cy: 21.865px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tdtjefb4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.308 14.78l22.341 2.317m-23.433 5.899l22.744 2.092m-23.491 6.228l22.568 1.01");
}

.w1b8kbsfz {
  cx: 10.547px;
  cy: 30.846px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x4wilq-dr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 2L3.156 29.128l3.168-.743l-3.407 3.51L2 42.5l29.642 2.562l.823-6.637l2.139 6.893L42.5 46l2.3-26.619l-3.687-4.207l4.019.366L46 5.5L18.316 3.108L16.778 6.97l-1.183-4.098Z");
}

</style>
