<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wcvp3gmoi"/><path class="naa-rvcjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:heart-half-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.naa-rvcjb {
  d: path("M178 40c-20.65 0-38.73 8.88-50 23.89C116.73 48.88 98.65 40 78 40a62.07 62.07 0 0 0-62 62c0 70 103.79 126.67 108.21 129a8 8 0 0 0 7.58 0C136.21 228.67 240 172 240 102a62.07 62.07 0 0 0-62-62M32 102a46.06 46.06 0 0 1 46-46c18.91 0 34.86 9.79 42 25.65V210c-26.41-16.56-88-60.22-88-108m104 108V81.65C143.14 65.79 159.09 56 178 56a46.06 46.06 0 0 1 46 46c0 47.71-61.58 91.41-88 108");
}

.wcvp3gmoi {
  d: path("M128 80v144S24 168 24 102a54 54 0 0 1 54-54c22.59 0 41.94 12.31 50 32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
