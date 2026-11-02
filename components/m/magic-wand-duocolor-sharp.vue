<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n09_q1bfx"/><path class="g19uql6wy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:magic-wand-duocolor-sharp" /></template>
<style>
.g19uql6wy {
  d: path("m3 21l10-10");
}

.n09_q1bfx {
  stroke-opacity: 0.4;
  d: path("M17 3c0 3.75.25 4 4 4c-3.75 0-4 .25-4 4c0-3.75-.25-4-4-4c3.75 0 4-.25 4-4M6 4v4M4 6h4m10 10v4m-2-2h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
