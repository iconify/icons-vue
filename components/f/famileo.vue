<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qgriibg3x"/><circle class="ane9pfbqe"/><circle class="f-7fwhn2z"/><path class="tmdgx1dms"/><path class="ejlkm7d1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:famileo" /></template>
<style>
.ane9pfbqe {
  cx: 39.233px;
  cy: 26.594px;
  r: 2.033px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ejlkm7d1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.024 26.594c5.692-5.286 16.752-5.204 20.33-3.253M21.75 43.67V26.188c-2.847.407-5.53 2.277-6.506 3.253m19.11-2.847c-2.44-1.22-5.693-1.22-5.693-1.22v18.297");
}

.f-7fwhn2z {
  cx: 25.002px;
  cy: 13.989px;
  r: 4.879px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qgriibg3x {
  cx: 10.771px;
  cy: 30.66px;
  r: 2.033px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tmdgx1dms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.354 9.517v34.154M15.65 43.67v-9.76c0-10.57-8.132-10.57-11.384-10.57");
}

</style>
