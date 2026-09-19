<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1bpycclk"/><circle class="umaxrfb5x"/><path class="buxvsrb_c"/><circle class="sg_2rzbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icon-pack-studio" /></template>
<style>
.buxvsrb_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.7 29.7L18.8 18.8");
}

.m1bpycclk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 27.5v-18c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h18");
}

.sg_2rzbkj {
  cx: 17.4px;
  cy: 17.4px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.umaxrfb5x {
  cx: 35px;
  cy: 35px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
