<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ieqnmm3zq"/><path class="pbk0dz_sa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-card-duocolor" /></template>
<style>
.ieqnmm3zq {
  stroke-opacity: 0.4;
  d: path("M8 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-1 8c0-1.105 1.343-2 3-2s3 .895 3 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pbk0dz_sa {
  d: path("M3 7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm12 4h3m-4 4h4");
}

</style>
