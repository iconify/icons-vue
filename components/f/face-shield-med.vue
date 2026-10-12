<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="wzovp8bkt"/><path class="nxcu2rb3p"/><path class="w8ehhfbko"/><path class="w194klbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-shield-med" /></template>
<style>
.nxcu2rb3p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8.25h14v6c0 4-3 7-7 7s-7-3-7-7Z");
}

.w194klbmu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 16h3m3-5.5v3.75c0 1.25-.5 2.5-1.25 3.25");
}

.w8ehhfbko {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.75h.01m4.99 0h.01");
}

.wzovp8bkt {
  width: 16px;
  height: 3px;
  x: 4px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
