<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="mex7lpbcq"/><rect class="p3-5u3vbz"/><path class="ed-xnxz9s"/><circle class="ctk1fcczq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hardware-key" /></template>
<style>
.ctk1fcczq {
  cx: 12px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ed-xnxz9s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 12h.01");
}

.mex7lpbcq {
  width: 14.75px;
  height: 9px;
  x: 2.75px;
  y: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.p3-5u3vbz {
  width: 3.75px;
  height: 5px;
  x: 17.5px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
