<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a9av1e0_m"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accounting-team" /></template>
<style>
.a9av1e0_m {
  d: path("M5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-2.5 13c0-3.75 2.75-6 6-6c1.278 0 2.455.306 3.398.789M13 7.5A3 3 0 1 1 18.598 9M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
