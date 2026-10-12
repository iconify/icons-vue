<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux32n0bfz"/><circle class="qv6z4dm_p"/><circle class="oicbsxx-q"/><circle class="s0kr5gbel"/><circle class="jwum6hb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-scatter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwum6hb4u {
  cx: 18px;
  cy: 7px;
  r: 1.5px;
}

.oicbsxx-q {
  cx: 12px;
  cy: 9.25px;
  r: 1.5px;
}

.qv6z4dm_p {
  cx: 8.75px;
  cy: 15.5px;
  r: 1.5px;
}

.s0kr5gbel {
  cx: 15.75px;
  cy: 14.5px;
  r: 1.5px;
}

.ux32n0bfz {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

</style>
