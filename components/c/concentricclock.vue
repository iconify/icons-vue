<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vg620duae"/><path class="j5_sk601k"/><path class="h56guabms"/><path class="mmgw152ds"/><path class="hqqzw7byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:concentricclock" /></template>
<style>
.h56guabms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.8 32.4a11.407 11.407 0 0 1-19-9.8a11.525 11.525 0 0 1 8.7-9.7a11.4 11.4 0 0 1 12.1 4.9m-2.7-7.3a15.6 15.6 0 0 1 5.9 5.2");
}

.hqqzw7byj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 21.6A22.84 22.84 0 0 1 9.7 8.2");
}

.j5_sk601k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.8 22.2a3.71 3.71 0 0 1 3.3-2a4.17 4.17 0 0 1 3.4 1.8m-3.6-5.6a7.6 7.6 0 0 1 6.7 3.5");
}

.mmgw152ds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 28.8a18.912 18.912 0 1 1-2.4-15.2");
}

.vg620duae {
  cx: 26.1px;
  cy: 24px;
  r: 0.5px;
  fill: currentColor;
}

</style>
