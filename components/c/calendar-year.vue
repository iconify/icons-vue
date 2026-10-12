<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ouoqrvbzc"/><path class="kpy15ccng"/><path class="t2mdzfbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-year" /></template>
<style>
.kpy15ccng {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 11.5h14.5M6.5 4h11.75a2.5 2.5 0 0 1 2.5 2.5v11.25");
}

.ouoqrvbzc {
  width: 14.5px;
  height: 14.25px;
  x: 3.25px;
  y: 7px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.t2mdzfbts {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01m3.49 0h.01M14 15h.01M7 18h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
