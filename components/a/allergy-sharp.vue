<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i9dxik6ec"/><path class="s0z9g6pbe"/><path class="p5q56jq7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:allergy-sharp" /></template>
<style>
.i9dxik6ec {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.85 6.26a2.45 2.45 0 1 1 1.45 4.48a2.45 2.45 0 1 1-3.8 2.76a2.45 2.45 0 1 1-3.8-2.76a2.45 2.45 0 1 1 1.45-4.48a2.45 2.45 0 1 1 4.7 0Z");
}

.p5q56jq7c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 4.75h.01m1.49 5.5h.01M16.5 14.5h.01");
}

.s0z9g6pbe {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM9.5 16v5.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
