<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m2bf2wcvg"/><path class="uiev5hq-h"/><circle class="hw3wgr08n"/><circle class="jj33i0bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adb-over-network" /></template>
<style>
.hw3wgr08n {
  cx: 27.505px;
  cy: 18.285px;
  r: 0.75px;
  fill: currentColor;
}

.jj33i0bdq {
  cx: 20.496px;
  cy: 18.285px;
  r: 0.75px;
  fill: currentColor;
}

.m2bf2wcvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 14.86C8.223 10.504 15.691 7.547 24 7.547s15.777 2.957 19.5 7.313L24 40.453Zm25.55.815zl1.496-1.389M16.189 14l1.787 1.66");
}

.uiev5hq-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.208a8.605 8.605 0 0 0-8.624 8.624v3.234h17.249v-3.234A8.605 8.605 0 0 0 24 13.208");
}

</style>
