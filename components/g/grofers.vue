<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ok7ytvxdr"/><circle class="cpk0fnbgt"/><path class="bra7z0exc"/><path class="ru9_4_b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grofers" /></template>
<style>
.bra7z0exc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.44 42.56c-11.59 0-17.07-9.31-17.07-11.72v-7.95a.63.63 0 0 1 .82-.61c2.61.83 10.81 3.3 15.89 3.3s13.28-2.47 15.92-3.3a.63.63 0 0 1 .82.61v8c-.03 2.36-4.82 11.67-16.38 11.67");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ok7ytvxdr {
  cx: 42.75px;
  cy: 5.25px;
  r: 2.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ru9_4_b7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.37 24a22.6 22.6 0 0 1-4.11-5.08m4.11 11.39c-1.25-.9-4-4.89-4.71-6M40.79 24a22.6 22.6 0 0 0 4.11-5.08m-4.11 11.39c1.25-.9 4-4.89 4.71-6");
}

</style>
