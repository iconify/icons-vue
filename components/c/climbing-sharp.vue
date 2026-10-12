<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="eak87tq9o"/><path class="s-e8k4b7c"/><path class="fsuwm8bkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:climbing-sharp" /></template>
<style>
.eak87tq9o {
  cx: 9px;
  cy: 5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fsuwm8bkx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 4.5h.01M5 12.5h.01");
}

.s-e8k4b7c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 8.75l.5 5M10.3 11l5.95-5.25M10.3 11l-3.8 1m4 1.75L14.75 16l.5 3.25m-4.75-5.5L7.75 17.5l1 3.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
