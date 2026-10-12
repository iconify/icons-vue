<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ob4r4xn_l"/><circle class="bpuhw68im"/><path class="hfdjq2bct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-door" /></template>
<style>
.bpuhw68im {
  cx: 11.25px;
  cy: 7px;
  r: 1.5px;
}

.hfdjq2bct {
  d: path("M11.25 10v4h3.5L16 17.25M8.9 12.4a3.5 3.5 0 1 0 4.6 4.85");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ob4r4xn_l {
  d: path("M4.75 21.25V4.75a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v16.5m-16.5 0h18.5");
}

</style>
