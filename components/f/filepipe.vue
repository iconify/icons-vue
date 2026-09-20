<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axqr63n9e"/><circle class="pr99dlj8u"/><circle class="aae2qibgc"/><circle class="p5gi8xb9k"/><path class="bbxoy9fxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filepipe" /></template>
<style>
.aae2qibgc {
  cx: 39.443px;
  cy: 20.998px;
  r: 3.057px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.axqr63n9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.912 35.208l1.71-2.96v-5.996a7.67 7.67 0 0 1-1.71-4.827c0-4.22 3.403-7.64 7.6-7.64h-.001h12.152a2.71 2.71 0 0 0-2.629-2.04h-13.3a3.6 3.6 0 0 1-2.102-.673l-4.44-3.167a3.6 3.6 0 0 0-2.102-.673H8.211a2.71 2.71 0 0 0-2.71 2.708V32.5a2.71 2.71 0 0 0 2.71 2.708z");
}

.bbxoy9fxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.51 24.055v10.599m10.933-10.599v4.327L28.51 31.873");
}

.p5gi8xb9k {
  cx: 28.51px;
  cy: 37.711px;
  r: 3.057px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pr99dlj8u {
  cx: 28.51px;
  cy: 20.998px;
  r: 3.057px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
