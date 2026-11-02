<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m-bdqibwy"/><path class="cesmxqb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-upload-duocolor-sharp" /></template>
<style>
.cesmxqb_w {
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6");
}

.m-bdqibwy {
  stroke-opacity: 0.4;
  d: path("m15 15l-3-3l-3 3m3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
