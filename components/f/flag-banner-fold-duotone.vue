<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vcf5zgbru"/><path class="ejkfl5bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flag-banner-fold-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ejkfl5bib {
  d: path("M238.73 43.67A8 8 0 0 0 232 40h-80a8 8 0 0 0-7.28 4.69L135.94 64H28a8 8 0 0 0-5.92 13.38L57.19 116l-35.11 38.62A8 8 0 0 0 28 168h73.09a8 8 0 0 0 7.28-4.69l8.78-19.31h62.43l-34.86 76.69a8 8 0 1 0 14.56 6.62l80-176a8 8 0 0 0-.55-7.64M95.94 152H46.08l27.84-30.62a8 8 0 0 0 0-10.76L46.08 80h82.59Zm90.91-24h-62.43l32.73-72h62.43Z");
}

.vcf5zgbru {
  d: path("m141.09 72l-40 88H28l40-44l-40-44Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
