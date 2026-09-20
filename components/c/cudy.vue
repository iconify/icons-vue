<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="sdlsocc3x"/><path class="sqzhws1aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cudy" /></template>
<style>
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

.sdlsocc3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 24.886v3.68a2.726 2.726 0 0 1-2.726 2.727a2.72 2.72 0 0 1-1.928-.798");
}

.sqzhws1aw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 20.388v4.498a2.726 2.726 0 1 1-5.453 0v-4.498m-15.817 0v4.498a2.726 2.726 0 1 0 5.453 0v-4.498m-.001 4.498v2.726m-8.088-1.372A2.726 2.726 0 0 1 9.5 24.886v-1.773a2.725 2.725 0 0 1 5.091-1.358m16 1.359a2.726 2.726 0 1 0-5.453 0v1.772a2.726 2.726 0 1 0 5.453 0m0 2.726V16.707");
}

</style>
