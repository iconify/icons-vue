<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ulitj_b_j"/><path class="w1yx1qbbl"/><path class="y740f7uyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien-ufo" /></template>
<style>
.ulitj_b_j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5a9.25 3.25 0 1 0 18.5 0a9.25 3.25 0 1 0-18.5 0");
}

.w1yx1qbbl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.66c0-3.66 2-5.91 4.5-5.91s4.5 2.25 4.5 5.91q-4.5-.82-9 0");
}

.y740f7uyi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 10h.01m3.49 0h.01M7.5 15.5h.01m4.49.75h.01m4.49-.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
