<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h1iir96hi"/><path class="aiyo6m0kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:best-rate" /></template>
<style>
.aiyo6m0kc {
  d: path("M6 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm9.5-3.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L15.5 13.75l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.h1iir96hi {
  d: path("M2.5 12L8 5.5h13.5v13H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
