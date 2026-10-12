<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="l8lqb1o_u"/><path class="nkwhnfxcf"/><rect class="zgh-tvy8y"/><path class="tjzjc1blh"/><rect class="j5ll2879m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:burger-stack" /></template>
<style>
.j5ll2879m {
  width: 16px;
  height: 2.5px;
  x: 4px;
  y: 18.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.l8lqb1o_u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5a7.5 3.75 0 0 1 15 0a.75.75 0 0 1-.75.75H5.25a.75.75 0 0 1-.75-.75");
}

.nkwhnfxcf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5h.01m4.99 0h.01");
}

.tjzjc1blh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13h8.25l1.25 1.75L14 13h6.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgh-tvy8y {
  width: 17.5px;
  height: 7px;
  x: 3.25px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

</style>
