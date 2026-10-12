<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fzh_ptbqe"/><rect class="xtsqm3hxj"/><rect class="nnwvhl0qe"/><circle class="lzsw5jwij"/><path class="mxvfb2okv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-camera" /></template>
<style>
.fzh_ptbqe {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 7.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lzsw5jwij {
  cx: 12px;
  cy: 13.75px;
  r: 3.75px;
}

.mxvfb2okv {
  d: path("M2.75 11.25H7m10 0h4.25");
}

.nnwvhl0qe {
  width: 4px;
  height: 3px;
  x: 15.5px;
  y: 4.75px;
  rx: 0.75px;
}

.xtsqm3hxj {
  width: 4px;
  height: 3px;
  x: 4.5px;
  y: 4.75px;
  rx: 0.75px;
}

</style>
