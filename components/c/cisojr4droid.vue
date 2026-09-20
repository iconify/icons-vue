<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="hq6ony3yx"/><path class="faub_1bzu"/><ellipse class="e-d3lkb4g"/><circle class="pgz061bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cisojr4droid" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e-d3lkb4g {
  cx: 23.841px;
  cy: 23.658px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.364px;
  ry: 2.503px;
}

.faub_1bzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.909 9.69q.258-.01.516-.01A13.55 13.55 0 0 1 36.99 23.22q0 .217-.007.434M21.117 36.562a13.56 13.56 0 0 1-10.583-9.13");
}

.hq6ony3yx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.163 41.545A17.65 17.65 0 0 1 6.517 27.463M22.909 6.48q.466-.025.933-.025a17.65 17.65 0 0 1 17.642 17.198");
}

.pgz061bvq {
  cx: 23.841px;
  cy: 23.652px;
  r: 6.019px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
