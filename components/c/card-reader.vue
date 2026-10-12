<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zew5mvpbd"/><rect class="vosc-3ipj"/><rect class="y1ejn3t2e"/><path class="p1x7434yb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:card-reader" /></template>
<style>
.p1x7434yb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 15.75h.01m1.99 0h.01");
}

.vosc-3ipj {
  width: 12px;
  height: 8px;
  x: 2.75px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y1ejn3t2e {
  width: 6.5px;
  height: 4px;
  x: 14.75px;
  y: 13.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zew5mvpbd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.25h3q1 0 1.71.71l.58.58q.71.71.71 1.71v3.5q0 1-1 1h-5q-1 0-1-1v-5.5q0-1 1-1");
}

</style>
