<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i-6g91b1w"/><path class="jkaziacri"/><circle class="ilo-8ib4d"/><circle class="t5en3db_l"/><circle class="p300j6bcm"/><circle class="gl6fg5boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canadaradar" /></template>
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

.gl6fg5boo {
  cx: 30.909px;
  cy: 30.94px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i-6g91b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.07 14.58a16 16 0 1 0 3.51-3.51");
}

.ilo-8ib4d {
  cx: 23.979px;
  cy: 24px;
  r: 4.43px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jkaziacri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.42 29a9.93 9.93 0 1 1 16.56.89M29.85 32a9.93 9.93 0 0 1-10.87.58");
}

.p300j6bcm {
  cx: 17.049px;
  cy: 30.93px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t5en3db_l {
  cx: 12.69px;
  cy: 12.69px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
