<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sxqr58bdg"/><circle class="nw_26ibjx"/><path class="bn940l_mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joystick-sharp" /></template>
<style>
.bn940l_mc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 18.4h.01m9.99 0h.01");
}

.nw_26ibjx {
  cx: 12px;
  cy: 6.5px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxqr58bdg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 15.5H21v5.75H3V15.5zm7.5 0V9.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
