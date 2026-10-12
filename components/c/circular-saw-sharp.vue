<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nr4dnrb4q"/><path class="yptca_bjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:circular-saw-sharp" /></template>
<style>
.nr4dnrb4q {
  d: path("m19 12.75l1.43 1.11l-1.67.7L19.85 16l-1.79.25l.68 1.67l-1.79-.22l.22 1.79l-1.67-.68l-.25 1.79l-1.44-1.09l-.7 1.67L12 19.75a7 7 0 1 1 7-7Zm-9 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yptca_bjx {
  d: path("M2.94 8.52a10 10 0 0 1 18.12 0");
}

</style>
