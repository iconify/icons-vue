<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yt0-8ac4z"/><path class="n-6s4pbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:label-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n-6s4pbeg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h4c.64 0 1.36.36 2 1l4 4a1.414 1.414 0 0 1 0 2l-4 4c-.64.64-1.36 1-2 1H6a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2z");
}

.yt0-8ac4z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6h4c.763 0 1.479.48 2 1l4 4a1.415 1.415 0 0 1 0 2l-4 4c-.521.52-1.237 1-2 1H6a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2Z");
}

</style>
