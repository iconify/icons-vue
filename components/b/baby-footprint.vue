<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c0hfuui6i"/><circle class="mwik7uw-h"/><path class="uljywb3_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-footprint" /></template>
<style>
.c0hfuui6i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5c2.75 0 4.25 2 4.25 4.75c0 2.25-1 3-1 4.5s-.75 2.5-3 2.5S8.75 20 8.75 18c0-1.75-1.25-2.5-1.25-4.25c0-2.5 1.75-4.25 4.5-4.25");
}

.mwik7uw-h {
  cx: 15.25px;
  cy: 5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uljywb3_d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 4.25h.01M8.5 5.5h.01M6.75 8h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
