<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="uykjb1pxr"/><path class="zg48z0bek"/><path class="s9r45ba6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:honor-ai-space" /></template>
<style>
.s9r45ba6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 24c0 8.077-5.373 14.625-12 14.625s-12-6.548-12-14.625c0-3.563 1.067-7.003 3.001-9.675M9.5 24h5m9.5 0h14.5");
}

.uykjb1pxr {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.5px;
  ry: 19.5px;
}

.zg48z0bek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 24c0-5.385 3.246-9.75 7.25-9.75S24 18.615 24 24h0c0 4.982-2.793 9.163-6.477 9.694");
}

</style>
