<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="d0p5x2b0x"/><path class="nyb4gfb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chemistry" /></template>
<style>
.d0p5x2b0x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4v6.33a6.25 6.25 0 0 1 4.23 6.42H5.77A6.25 6.25 0 0 1 10 9.08ZM5.77 15.5h12.46a6.25 6.25 0 0 1-12.46 0");
}

.nyb4gfb3a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 4h.01m1.99 3.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
