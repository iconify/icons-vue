<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="wiwtxbbiz"/><path class="bxcdgwb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cudy" /></template>
<style>
.bxcdgwb3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 20.388v4.498a2.726 2.726 0 0 1-2.726 2.726h0a2.726 2.726 0 0 1-2.727-2.726v-4.498m-15.817 0v4.498a2.726 2.726 0 0 0 2.726 2.726h0a2.726 2.726 0 0 0 2.726-2.726v-4.498m0 4.498v2.726m-8.088-1.372a2.73 2.73 0 0 1-2.368 1.372h0A2.726 2.726 0 0 1 9.5 24.886v-1.772a2.726 2.726 0 0 1 2.726-2.726h0c1.012 0 1.894.55 2.365 1.368m16 1.358a2.726 2.726 0 0 0-2.726-2.726h0a2.726 2.726 0 0 0-2.726 2.726v1.772a2.726 2.726 0 0 0 2.726 2.726h0a2.726 2.726 0 0 0 2.726-2.726m0 2.726V16.707");
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

.wiwtxbbiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 24.886v3.68a2.726 2.726 0 0 1-2.726 2.727h0a2.72 2.72 0 0 1-1.928-.798");
}

</style>
