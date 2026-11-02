<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ya8ptbcij"/><path class="f__g6fbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-duotone-round" /></template>
<style>
.f__g6fbmx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l4-4a4.243 4.243 0 0 1 6 6l-4 4zm1 1l-4 4c-.64.64-1 1.36-1 2v1a1 1 0 0 0 1 1h3c.64 0 1.36-.36 2-1l3-3");
}

.ft5dv1b6b {
  fill: none;
}

.ya8ptbcij {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.293 6.293a5.243 5.243 0 0 1 7.414 7.414l-4 4a1 1 0 0 1-1.414 0l-6-6a.997.997 0 0 1 0-1.414Z");
}

</style>
