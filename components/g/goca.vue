<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="p1um_wbqu"/><path class="ofpbglyjc"/><path class="dwvj2ccmr"/><path class="hr7w1tbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goca" /></template>
<style>
.dwvj2ccmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.646a4.58 4.58 0 0 1 6.232.752l1.92 2.287a4.58 4.58 0 0 1-.567 6.47a4.58 4.58 0 0 1-6.47-.567L5.5 35.26m26.726-17.185c.282 1.567-.26 3.238-1.886 4.602c-1.625 1.363-4.522 1.11-6.152-.833l-1.919-2.287c-1.63-1.943-1.377-4.84.247-6.202s3.36-1.608 4.852-1.062m12.181-3.338c1.63 1.943 1.389 4.83-.54 6.447l-1.225 1.028c-1.277 1.072-3.188.897-4.268-.39s-.92-3.2.357-4.271l4.723-3.963");
}

.hr7w1tbim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.297 9.24c.135-1.561.667-2.134 2.303-3.507q.147-.123.294-.235m4.671 0q.327.291.652.678l5.284 6.297M13.474 26.937a4.592 4.592 0 0 1 7.036-5.904l1.918 2.287a4.592 4.592 0 0 1-7.035 5.904z");
}

.ofpbglyjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.763 24.895l8.856 10.554a4.592 4.592 0 0 1-1.45 7.053");
}

.p1um_wbqu {
  width: 37px;
  height: 37px;
  x: 5.501px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
