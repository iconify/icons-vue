<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrxzbzbtn"/><path class="uz0uapbhg"/><path class="w7iyvqysj"/><path class="of8hu9b6a"/><circle class="pgeu3konp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:isotopebrowser" /></template>
<style>
.mrxzbzbtn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.648 39.375c-3.729.86-6.906-8.873-7.864-14.287S15.334 9.262 19.32 8.603s6.881 9.403 7.785 14.808s1.27 15.104-2.458 15.964");
}

.of8hu9b6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.408 12.174c2.158 1.405-.538 9.908-2.802 14.1s-8.075 11.02-10.163 9.833s.717-10.337 3.02-14.506s7.788-10.832 9.945-9.427");
}

.pgeu3konp {
  cx: 22.047px;
  cy: 24.089px;
  r: 0.8px;
  fill: currentColor;
}

.uz0uapbhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.548 19.785c.917-3.6 14.389-3.429 21.178-1.957s18.638 6.447 17.724 10.13s-13.495 4.159-20.37 2.772S3.63 23.385 4.548 19.785");
}

.w7iyvqysj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.41 30.159c-1.172-2.476 6.947-8.58 11.692-10.727s14.16-4.144 15.294-1.65s-6.368 8.234-11.084 10.444s-14.73 4.41-15.902 1.933");
}

</style>
