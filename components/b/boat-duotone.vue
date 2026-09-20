<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="x3--v6bdf"/><path class="bcxpr4aso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:boat-duotone" /></template>
<style>
.bcxpr4aso {
  d: path("M221.06 110.59L208 106.23V56a16 16 0 0 0-16-16h-56V24a8 8 0 0 0-16 0v16H64a16 16 0 0 0-16 16v50.23l-13.06 4.36A16 16 0 0 0 24 125.77V152c0 61.54 97.89 86.72 102.06 87.76a8 8 0 0 0 3.88 0C134.11 238.72 232 213.54 232 152v-26.23a16 16 0 0 0-10.94-15.18M64 56h128v44.9l-61.47-20.49a8 8 0 0 0-5.06 0L64 100.9Zm152 96c0 24.91-23.68 43-43.55 53.83A228 228 0 0 1 128 223.72A227 227 0 0 1 83.81 206C47.6 186.35 40 165.79 40 152v-26.23l80-26.67V168a8 8 0 0 0 16 0V99.1l80 26.67Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.x3--v6bdf {
  d: path("M224 125.77V152c0 56-96 80-96 80s-96-24-96-80v-26.23a8 8 0 0 1 5.47-7.59L128 88l90.53 30.18a8 8 0 0 1 5.47 7.59");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
