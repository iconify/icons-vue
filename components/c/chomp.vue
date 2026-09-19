<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="puz-izb7g"/><circle class="oell4eb7w"/><circle class="ff034cbai"/><path class="mucsx0bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chomp" /></template>
<style>
.ff034cbai {
  cx: 29.334px;
  cy: 15.447px;
  r: 2.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mucsx0bli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.236 23.604a12.68 12.68 0 0 0 8.754 3.472c3.41 0 6.487-1.31 8.774-3.472");
}

.oell4eb7w {
  cx: 18.736px;
  cy: 15.447px;
  r: 2.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.puz-izb7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 7.3h-33a3 3 0 0 0-3 3v20a3 3 0 0 0 3 3h1.64v7.4l8.26-7.4h23.1a3 3 0 0 0 3-3v-20a3 3 0 0 0-3-3");
}

</style>
