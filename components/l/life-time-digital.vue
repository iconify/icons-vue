<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cfdm1gbhr"/><circle class="nx479r79w"/><circle class="cw0_ftbyq"/><circle class="z9vy0jplm"/><path class="m626gbipp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:life-time-digital" /></template>
<style>
.cfdm1gbhr {
  cx: 24px;
  cy: 19.975px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cw0_ftbyq {
  cx: 40.1px;
  cy: 19.975px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m626gbipp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.575v14.85h22.9v-6.8H11.3v-8.05z");
}

.nx479r79w {
  cx: 32.05px;
  cy: 19.975px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z9vy0jplm {
  cx: 32.05px;
  cy: 28.025px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
