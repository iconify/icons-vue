<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="m-ff1gbzq"/><path class="gkeweqb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acalendar-plus" /></template>
<style>
.gkeweqb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 4.5v6m-19-6v6m14.848 17.738A5.35 5.35 0 0 1 24 33.587h0a5.35 5.35 0 0 1-5.348-5.349v-3.476A5.35 5.35 0 0 1 24 19.413h0a5.35 5.35 0 0 1 5.348 5.349m2.14 8.825a2.14 2.14 0 0 1-2.14-2.14V19.413M31.984 17h5.273m-2.637-2.636v5.272");
}

.m-ff1gbzq {
  width: 35px;
  height: 36px;
  x: 6.5px;
  y: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
