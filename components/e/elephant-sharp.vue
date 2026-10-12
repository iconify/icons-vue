<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i-5qb4b-b"/><path class="s70kiccph"/><path class="h-_mr525x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elephant-sharp" /></template>
<style>
.h-_mr525x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 9.75h.01");
}

.i-5qb4b-b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 6h5c3.6 0 6.5 2.9 6.5 6.5v8.75h-3.5V17.5h-5v3.75h-3.5V15.5c-2.85-.4-4.5-2.1-4.5-4.5c0-2.75 2.25-5 5-5Z");
}

.s70kiccph {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5v6H3v-1.25m7.25-9c3-1 6.25.25 6.25 3.25c0 2.25-1.75 3.5-3.75 3.5H10.5v-1.5c0-.9.6-1.4.6-2.65v-1.325z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
