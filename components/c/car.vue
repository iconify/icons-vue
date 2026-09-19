<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bvbp1f0mw"/><rect class="r2-80lbbe"/><path class="l5fvasbrn"/><circle class="wkyuzkbcw"/><path class="ot1z6nbyn"/><circle class="a_pfb_86e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:car" /></template>
<style>
.a_pfb_86e {
  cx: 37.371px;
  cy: 29.46px;
  r: 2.229px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bvbp1f0mw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 36.146s-.194 1.51 0 2.228c.135.498.264 1.337.78 1.337h2.897c.516 0 .645-.839.78-1.337c.194-.717 0-2.228 0-2.228");
}

.l5fvasbrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.143 36.146s-.194 1.51 0 2.228c.135.498.264 1.337.78 1.337h2.897c.516 0 .645-.839.78-1.337c.194-.717 0-2.228 0-2.228");
}

.ot1z6nbyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.957 21.66l2.563-10.029c.438-1.713 2.353-3.343 4.123-3.343h16.714c1.77 0 3.685 1.63 4.123 3.343l2.563 10.029");
}

.r2-80lbbe {
  width: 39px;
  height: 14.486px;
  x: 4.5px;
  y: 21.66px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.457px;
  ry: 4.457px;
}

.wkyuzkbcw {
  cx: 10.629px;
  cy: 29.46px;
  r: 2.229px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
