<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyrph548t"/><path class="b471jc4fl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banco-estado" /></template>
<style>
.b471jc4fl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.708 26.5v-4.05l-.013.012h0L5.5 28.25v4.05zm10.609 9.837H42.5V18.988L29.305 8.213zm13.183.001h-37");
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

.xyrph548t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.708 36.338h10.596V8.211h0a17.5 17.5 0 0 1-10.609 5.925h0v4.188L5.5 24.113v4.137l13.195-5.788v-4.137l4.237-1.85v4.1l-4.224 1.875v4.05l4.236-1.85v4.037l-4.236 1.863V26.5L5.5 32.287v4.05l13.208-5.787z");
}

</style>
