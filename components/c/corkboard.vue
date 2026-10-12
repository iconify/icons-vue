<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f0ob_2b3h"/><path class="i0_zsfb4j"/><path class="nwc26uc6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corkboard" /></template>
<style>
.f0ob_2b3h {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.i0_zsfb4j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7h4.5v6h-4.5Zm6.75 2h5.75v7.5H12.5Z");
}

.nwc26uc6p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9.5h.01m7.39 2h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
