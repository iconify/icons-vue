<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ig5w3jh4s"/><path class="z0czg0bsi"/><path class="q6icwma0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crow-sharp" /></template>
<style>
.ig5w3jh4s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6.25V4.5h5.083L13 7c3 1 5.25 3.25 6.25 5.75l1.7 2.6l.47.657l-.62.443l-.75.55l-.54.36l-.41-.41l-2.6-1.45l-2.083 1.5H12c-3 0-5.25-2-5.25-4.75v-2.167L8 8l-.5-.643z");
}

.q6icwma0c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z0czg0bsi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 5.6L3.25 7.15L1.9 7.6l1.35.45L7.5 9.1Zm3.15 11.3l-.5 4.35H9m4.5-4.5l.5 4.5h1.25");
}

</style>
