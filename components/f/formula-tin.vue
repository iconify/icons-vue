<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zxt2az7as"/><path class="bhaxp4yuf"/><rect class="a_7sod_cd"/><path class="fmpif9znc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:formula-tin" /></template>
<style>
.a_7sod_cd {
  width: 15px;
  height: 13.75px;
  x: 4.5px;
  y: 7.5px;
  rx: 2.5px;
}

.bhaxp4yuf {
  d: path("M14.5 4H11");
}

.fmpif9znc {
  d: path("M4.5 11h15M8 14h8v4.25H8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxt2az7as {
  cx: 15.75px;
  cy: 4px;
  r: 1.25px;
}

</style>
