<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="fedqdacgc"/><path class="dmaj9ybus"/><path class="pz0-o4mrr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:blemonitor" /></template>
<style>
.dmaj9ybus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.45 19.27a5.59 5.59 0 0 1 5.63 5.63m-5.63-10.62c5.845.049 10.571 4.775 10.62 10.62");
}

.fedqdacgc {
  cx: 17.45px;
  cy: 24.9px;
  r: 1.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.pz0-o4mrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.45 9.08c8.693.017 15.727 7.077 15.71 15.77v.05M17.5 30v8.2h4.1m2 0h4.1M23.6 30h4.1m-4.1 4.1h2.7M23.6 30v8.2m6.2 0V30l4.1 8.2L38 30v8.2m-24.6-4.1a2 2 0 1 1 0 4H10v-8.2h3.4a2 2 0 0 1 2 2a2.19 2.19 0 0 1-2 2.2m0 0H10");
}

</style>
