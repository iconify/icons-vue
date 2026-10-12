<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="e0tvxkbxk"/><path class="z5vhowmcy"/><circle class="g11y-v37c"/><path class="ghx4t3bny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delivery-time" /></template>
<style>
.e0tvxkbxk {
  width: 11.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 1.25px;
}

.g11y-v37c {
  cx: 16.75px;
  cy: 7.25px;
  r: 4.5px;
}

.ghx4t3bny {
  d: path("M16.75 5.25v2l1.5 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5vhowmcy {
  d: path("M8.5 8.75v3.5");
}

</style>
