<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gda666b6t"/><path class="phx2_obuf"/><path class="tv4x0bbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chipmunk-sharp" /></template>
<style>
.gda666b6t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5c0-2.75 2-4.75 4.5-4.75h.667L10 5l1-1.5l.5 2l1.847 1.33l.403 2.42C16 10.5 17.5 13 17.5 15.75c0 3-2.25 5-5.25 5H6.568l.682-1.85l1-3.9L4 13.3z");
}

.phx2_obuf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.25 10l3.351 1.256L15 15.25m2 3c2.25-.75 3.5-2.75 3.5-5.25c0-2.25-.75-4-2-5.5");
}

.tv4x0bbnc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 8.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
