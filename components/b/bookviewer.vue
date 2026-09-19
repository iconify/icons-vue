<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sgfyceq5m"/><path class="oqhxvhb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bookviewer" /></template>
<style>
.oqhxvhb0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.508 8.378v14.74l-4.254-3.727l-4.255 3.727V8.393");
}

.sgfyceq5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.254a22 22 0 0 0-9.433-2.284A22 22 0 0 0 4.5 10.254v29.779a22.04 22.04 0 0 1 10.067-2.285A22 22 0 0 1 24 40.033zm0 0a22 22 0 0 1 9.433-2.284A22 22 0 0 1 43.5 10.254v29.779a22.04 22.04 0 0 0-10.067-2.285A22 22 0 0 0 24 40.033z");
}

</style>
