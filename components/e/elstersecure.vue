<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGt6OZIecq" class="vdon5vbwf"/><path id="SVGNEWJMvPo" class="ymc92cl8q"/></defs><path class="i_hagkb6c"/><use href="#SVGt6OZIecq" class="c-zrgpb5l"/><path class="icgqaacnk"/><use href="#SVGt6OZIecq" class="c-zrgpb5l"/><use href="#SVGNEWJMvPo" class="c-zrgpb5l"/><use href="#SVGNEWJMvPo" class="c-zrgpb5l"/><path class="x6u2ichsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elstersecure" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i_hagkb6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c9.043-3.117 15.489-10.363 16.5-19.589c.28-4.005.257-8.025-.071-12.027a2.54 2.54 0 0 0-2.468-2.366c-4.091-.126-8.846-.808-12.52-4.427a2.05 2.05 0 0 0-2.881 0c-3.675 3.619-8.43 4.301-12.52 4.427a2.54 2.54 0 0 0-2.468 2.366A79.4 79.4 0 0 0 7.5 23.911C8.512 33.137 14.957 40.383 24 43.5m0-29.176v9.493");
}

.icgqaacnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.421 31.5L24 23.817v-.018");
}

.vdon5vbwf {
  fill: none;
  stroke: currentColor;
  d: path("M14.964 20.872L24 23.799v.018");
}

.x6u2ichsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.036 20.872L24 23.799v.018");
}

.ymc92cl8q {
  fill: none;
  stroke: currentColor;
  d: path("M18.421 31.5L24 23.817v-.018m5.579 7.701L24 23.817v-.018");
}

</style>
