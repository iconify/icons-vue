<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pn5qxlb1s"/><rect class="kmuphbbge"/><path class="cykxfgb2d"/><path class="we78tsbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion-dance-head" /></template>
<style>
.cykxfgb2d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 10.25h.01m5.49 0h.01");
}

.kmuphbbge {
  width: 12px;
  height: 15.25px;
  x: 6px;
  y: 6px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 4px;
}

.pn5qxlb1s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6V2.75");
}

.we78tsbnp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 14.25h8a4 3.25 0 0 1-8 0M3.75 9a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2m16.5-8a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
