<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mgh-g6hkn"/><path class="zyxhuxbbz"/><circle class="g2ql4oemh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:camera" /></template>
<style>
.g2ql4oemh {
  cx: 38.5px;
  cy: 17.02px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mgh-g6hkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.92a8.5 8.5 0 1 1-8.5 8.5h0a8.5 8.5 0 0 1 8.5-8.5");
}

.zyxhuxbbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 12.02h-8l-2.594-4h-9.812l-2.594 4h-8a4 4 0 0 0-4 4v18.8a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-18.8a4 4 0 0 0-4-4");
}

</style>
