<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sucb75d-l"/><path class="wyyi7-bot"/><path class="ym436nbtd"/><circle class="a2u0h6mgd"/><path class="ik9lg5brw"/><path class="xlqzodbpd"/><path class="f-l5r1p-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:funktrainer" /></template>
<style>
.a2u0h6mgd {
  cx: 24px;
  cy: 18.196px;
  r: 2.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f-l5r1p-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.745 9.978a9.49 9.49 0 0 1 0 16.436");
}

.ik9lg5brw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5V20.305M31.908 4.5a15.815 15.815 0 0 1 0 27.392");
}

.sucb75d-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.093 31.892a15.815 15.815 0 0 1 0-27.392");
}

.wyyi7-bot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.674 29.153a12.652 12.652 0 0 1 0-21.914");
}

.xlqzodbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.326 7.24a12.652 12.652 0 0 1 0 21.913");
}

.ym436nbtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.256 26.414a9.49 9.49 0 0 1 0-16.436");
}

</style>
