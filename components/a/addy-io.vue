<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="br5inc1lc"/><path class="mvpkwwbid"/><path class="nkys0zb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:addy-io" /></template>
<style>
.br5inc1lc {
  width: 11.747px;
  height: 11.747px;
  x: 18.127px;
  y: 23.531px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.349px;
  ry: 2.349px;
}

.mvpkwwbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.35 43.5h-8.223a8.223 8.223 0 0 1-8.223-8.223V23.531a8.223 8.223 0 0 1 8.223-8.223h11.746a8.223 8.223 0 0 1 8.223 8.223v3.524a8.223 8.223 0 0 1-8.223 8.222h-2.349");
}

.nkys0zb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.29 15.812v-2.561a8.75 8.75 0 1 1 17.502 0v2.561");
}

</style>
