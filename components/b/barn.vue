<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bb2-dcb8p"/><rect class="zvw62kbzs"/><path class="l414i2bgs"/><circle class="jbk3eiaid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barn" /></template>
<style>
.bb2-dcb8p {
  d: path("M3 20.45V11.8q0-.8.39-1.5l1.72-3.1q.39-.7 1.12-1.04l5.04-2.32q.73-.34 1.46 0l5.04 2.32q.73.34 1.12 1.04l1.72 3.1q.39.7.39 1.5v8.65q0 .8-.8.8H3.8q-.8 0-.8-.8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbk3eiaid {
  cx: 12px;
  cy: 9.25px;
  r: 1.25px;
}

.l414i2bgs {
  d: path("m9.25 14.75l5.5 5.75m0-5.75l-5.5 5.75");
}

.zvw62kbzs {
  width: 7px;
  height: 7.25px;
  x: 8.5px;
  y: 14px;
  rx: 0.5px;
}

</style>
