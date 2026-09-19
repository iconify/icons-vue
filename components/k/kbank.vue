<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="evwnaxbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kbank" /></template>
<style>
.evwnaxbxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.498 20v8m0-1.699l3.63-3.604m-2.47 2.457l2.84 2.834M26.15 26a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3m5.674 5.3v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3m-11.348 2a2 2 0 1 1 4 0V26a2 2 0 1 1-4 0m0 2v-8m-5.974 0v8m0-2.786l4.3-5.187m0 7.973l-3.29-4");
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

</style>
