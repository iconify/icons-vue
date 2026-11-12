<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n8szyl_bj"/><path class="p9b2a5bfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-subtract-duocolor" /></template>
<style>
.n8szyl_bj {
  stroke-opacity: 0.4;
  d: path("M19 9h1a1 1 0 0 1 1 1v3m0 4v3a1 1 0 0 1-1 1h-3m-8-2v1a1 1 0 0 0 1 1h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9b2a5bfl {
  d: path("M9 3h5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 0-1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1z");
}

</style>
