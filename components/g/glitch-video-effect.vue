<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="x37aykbwn"/><path class="zb7v9vbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glitch-video-effect" /></template>
<style>
.x37aykbwn {
  width: 33.13px;
  height: 28.044px;
  x: 6.587px;
  y: 9.978px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.239px;
  ry: 7.239px;
}

.zb7v9vbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21.326h4.174m-4.174 6h4.174M5.772 24h6.815m24.848-1.826H42m-.783 2.478h-6m3.653-6.065h4.63m-.978 8.739h-4.826m-9.591-4.374l-6.369-3.677a1.21 1.21 0 0 0-1.815 1.048v7.354a1.21 1.21 0 0 0 1.815 1.048l6.369-3.677a1.21 1.21 0 0 0 0-2.096");
}

</style>
