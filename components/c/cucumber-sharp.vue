<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pcx8i6l6y"/><path class="o3bi57sdq"/><circle class="iwer1wtdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cucumber-sharp" /></template>
<style>
.iwer1wtdo {
  cx: 18px;
  cy: 18px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o3bi57sdq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M13 10h.01");
}

.pcx8i6l6y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.13 14.63l10-10a3 3 0 0 1 4.24 4.24l-10 10a3 3 0 0 1-4.24-4.24Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
