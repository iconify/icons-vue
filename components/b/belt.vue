<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="thm59gbch"/><rect class="r7so-bbux"/><path class="vwgqqw39o"/><path class="th7iub40n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:belt" /></template>
<style>
.r7so-bbux {
  width: 6.5px;
  height: 10.5px;
  x: 7.5px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.th7iub40n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 12h.01m2.49 0h.01");
}

.thm59gbch {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.vwgqqw39o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12h5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
