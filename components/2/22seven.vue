<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i7kzmwbil"/><circle class="bnp_nv68d"/><path class="tjwe7ob5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:22seven" /></template>
<style>
.bnp_nv68d {
  cx: 33.66px;
  cy: 24px;
  r: 6.976px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i7kzmwbil {
  cx: 14.34px;
  cy: 24px;
  r: 6.976px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tjwe7ob5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.364 24H3.5m41 0h-3.864m-19.729-2.325a6.7 6.7 0 0 1 3.198-.805c1.084 0 2.115.258 3.016.72");
}

</style>
