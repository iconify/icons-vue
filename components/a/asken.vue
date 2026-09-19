<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qy75zabpp"/><circle class="bo48t3bhw"/><circle class="is3vryt7x"/><path class="m8wi27b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asken" /></template>
<style>
.bo48t3bhw {
  cx: 30.099px;
  cy: 28.846px;
  r: 0.75px;
  fill: currentColor;
}

.is3vryt7x {
  cx: 32.792px;
  cy: 31.335px;
  r: 0.75px;
  fill: currentColor;
}

.m8wi27b_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.99 14.36V5.5m2.264 3.258L30.573 7.6");
}

.qy75zabpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.407 26.358l-4.137-3.751l-5.404 5.404l-8.523-7.727c1.569-5.584 6.11-9.18 14.647-5.924c24.013-9.157 16.405 35.887 0 26.964c-8.663 4.712-14.873-5.626-15.269-15.084");
}

</style>
