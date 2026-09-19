<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="w5ztvbg7m"/><path class="w9v12qzbx"/></g><path class="t-1w98bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acalendar" /></template>
<style>
.t-1w98bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.348 28.238A5.35 5.35 0 0 1 24 33.587h0a5.35 5.35 0 0 1-5.348-5.349v-3.476A5.35 5.35 0 0 1 24 19.413h0a5.35 5.35 0 0 1 5.348 5.349m2.14 8.825a2.14 2.14 0 0 1-2.14-2.14V19.413");
}

.w5ztvbg7m {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  rx: 4px;
  ry: 4px;
}

.w9v12qzbx {
  d: path("M33.5 4.5v6m-19-6v6");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
