<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z3klpsb_l"/><path class="jch6wpblh"/><path class="tv4x0bbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chipmunk" /></template>
<style>
.jch6wpblh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 10c2 .75 3.5 2.75 3.75 5.25m2 3c2.25-.75 3.5-2.75 3.5-5.25c0-2.25-.75-4-2-5.5");
}

.tv4x0bbnc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 8.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z3klpsb_l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5c0-2.75 2-4.75 4.5-4.75c.5 0 1 .1 1.5.25l1-1.5l.5 2c1.25.9 2 2.25 2.25 3.75C16 10.5 17.5 13 17.5 15.75c0 3-2.25 5-5.25 5H8.5c-1 0-1.6-.9-1.25-1.85l1-3.9C5.75 14 4 12 4 9.5");
}

</style>
