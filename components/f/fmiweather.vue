<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mkg5aj2jw"/><path class="c4vbohbew"/><path class="xpj7kqb1t"/><path class="toppu73mg"/><path class="pdlz5ob5g"/><path class="ridrcib9t"/><path class="hf1q9wmac"/><path class="d9zoq9bmm"/><path class="y460cx0_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fmiweather" /></template>
<style>
.c4vbohbew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.182 41.719a18.977 18.977 0 0 1 0-35.437");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d9zoq9bmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.854 14.208a9.908 9.908 0 0 1 0 19.584");
}

.hf1q9wmac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.69 9.99a14.442 14.442 0 0 1 0 28.02");
}

.mkg5aj2jw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.581 44.474a23.508 23.508 0 0 1 0-40.948");
}

.pdlz5ob5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.833 29.334a5.376 5.376 0 0 1 0-10.668M17.419 3.526a23.508 23.508 0 0 1 0 40.948");
}

.ridrcib9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.818 6.282a18.977 18.977 0 0 1 0 35.436");
}

.toppu73mg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.146 33.792a9.908 9.908 0 0 1 0-19.584");
}

.xpj7kqb1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.31 38.01a14.442 14.442 0 0 1 0-28.02");
}

.y460cx0_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.167 18.666a5.376 5.376 0 0 1 0 10.668M2.5 24h43");
}

</style>
