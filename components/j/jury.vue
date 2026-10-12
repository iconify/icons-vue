<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dng9h31fp"/><circle class="xpr56mbyr"/><path class="duuwzrlsj"/><rect class="iegp0u62x"/><path class="c3-nxnbjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jury" /></template>
<style>
.c3-nxnbjd {
  d: path("M8.25 15.5v3.25m7.5-3.25v3.25");
}

.dng9h31fp {
  cx: 8.25px;
  cy: 5.25px;
  r: 2.5px;
}

.duuwzrlsj {
  d: path("M5 10.25h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iegp0u62x {
  width: 18.5px;
  height: 8.25px;
  x: 2.75px;
  y: 13px;
  rx: 2px;
}

.xpr56mbyr {
  cx: 15.75px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
