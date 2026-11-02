<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dypmmjaoe"/><path class="d59be9sai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-duocolor" /></template>
<style>
.d59be9sai {
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.dypmmjaoe {
  stroke-opacity: 0.4;
  d: path("m3 17l5-5a1.414 1.414 0 0 1 2 0l3 3a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l3 3m-7-9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
