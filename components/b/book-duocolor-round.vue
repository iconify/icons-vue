<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oak4c5bhj"/><path class="k8nc2n2mm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-duocolor-round" /></template>
<style>
.k8nc2n2mm {
  d: path("M7 17h10a2 2 0 0 0 2-2V7a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v12m2-2a2 2 0 1 0 0 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oak4c5bhj {
  stroke-opacity: 0.4;
  d: path("M7 21h6a4 4 0 0 0 4-4");
}

</style>
