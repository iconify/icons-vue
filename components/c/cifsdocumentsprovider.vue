<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyq6x5yxx"/><circle class="ghlrf_b2r"/><circle class="llnh2hblj"/><circle class="lj2vhtqrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cifsdocumentsprovider" /></template>
<style>
.ghlrf_b2r {
  cx: 26.642px;
  cy: 35.952px;
  r: 1.887px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lj2vhtqrq {
  cx: 36.581px;
  cy: 41.613px;
  r: 1.887px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.llnh2hblj {
  cx: 36.581px;
  cy: 30.29px;
  r: 1.887px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xyq6x5yxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.097 8.44a1.215 1.215 0 0 0-1.258-1.172H26.516C25.161 7.202 23.644 4.5 22.113 4.5h-7.959a1.46 1.46 0 0 0-1.476 1.475v17.2a1.46 1.46 0 0 0 1.47 1.454H37.62a1.47 1.47 0 0 0 1.477-1.454ZM8.903 35.323h10.065m-5.033-5.662v5.662m14.326-.339l6.662-3.79m-6.633 5.672l6.618 3.88");
}

</style>
