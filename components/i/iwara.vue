<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ow0zo9b3c"/><path class="ftr2leb0l"/><path class="zw0_jic0r"/><path class="onwpthbct"/><path class="u2dj57uig"/><circle class="c4bzkib3d"/><circle class="tg0b9bn9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iwara" /></template>
<style>
.c4bzkib3d {
  cx: 30.304px;
  cy: 13.159px;
  r: 0.75px;
  fill: currentColor;
}

.ftr2leb0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.33 11.488a16.8 16.8 0 0 1 4.957-.497c1.904-.18 1.448 2.41-.54 5.15a13.26 13.26 0 0 1-5.488 4.437m-3.57-.833c1.333.82 1.998 1.191 3.57.833c11.192 8.9 3.758 20.604-2.98 21.923");
}

.onwpthbct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.86 25.792c1.845 1.027 3.146 2.135 3.43 3.29c.903 3.657-1.414 6.565-5.878 7.57a14.05 14.05 0 0 1-12.683-3.71m13.19-23.927c-1.59-.01-4.48 3.284-3.883 5.347");
}

.ow0zo9b3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.022 20.748c-6.041-9.805.826-15.383 6.972-15.247c6.369.142 12.599 6.716 3.695 14.244");
}

.tg0b9bn9p {
  cx: 11.155px;
  cy: 31.249px;
  r: 0.75px;
  fill: currentColor;
}

.u2dj57uig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.755 28.064l.402 2.273l-3.348.4m5.891-2.539l-2.945-.134m3.528-11.589v.004");
}

.zw0_jic0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.28 42.5l-15.667-.2C.965 39.036 5.84 20.96 7.709 20.98c10.778 4.46 15.445-.72 13.313-.232");
}

</style>
