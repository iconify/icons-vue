<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5xge1bgl"/><path class="e11rnwbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:api-duocolor" /></template>
<style>
.d5xge1bgl {
  stroke-opacity: 0.4;
  d: path("M10 12h4");
}

.e11rnwbgh {
  d: path("m7 8l-4 4l4 4m10-8l4 4l-4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
