<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="abt24ibfe"/><path class="tzfxgqboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:e-unicycle" /></template>
<style>
.abt24ibfe {
  d: path("M4.75 14.25a7.25 7.25 0 1 0 14.5 0a7.25 7.25 0 1 0-14.5 0ZM7 4.5c0-1.5 2-2 5-2s5 .5 5 2Zm5 0v7");
}

.tzfxgqboa {
  d: path("M9.5 11.5h5V17h-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
