<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="o5vw8-4ru"/><path class="xh7_6nb5j"/><path class="x4zkhdclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flux-2" /></template>
<style>
.o5vw8-4ru {
  cx: 17.343px;
  cy: 24.701px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.843px;
  ry: 12.87px;
}

.x4zkhdclo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.813 21.613h5.712a7.976 7.976 0 0 1 0 15.95H16.354");
}

.xh7_6nb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.859 14.068a7.839 7.839 0 0 1 13.449 8.044");
}

</style>
