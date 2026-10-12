<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ubdgkljhz"/><path class="lh3a2fbrj"/><rect class="ihd60yf_v"/><path class="a7b1c27vx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-blame" /></template>
<style>
.a7b1c27vx {
  d: path("M15.25 8h3m-3 4h3m-3 4H17");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihd60yf_v {
  width: 9px;
  height: 18.5px;
  x: 12.25px;
  y: 2.75px;
  rx: 2.5px;
}

.lh3a2fbrj {
  d: path("M2.75 16.75a3.5 3.5 0 0 1 7 0v.5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1Z");
}

.ubdgkljhz {
  cx: 6.25px;
  cy: 8px;
  r: 2.5px;
}

</style>
