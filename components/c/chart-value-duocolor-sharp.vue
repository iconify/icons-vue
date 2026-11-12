<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jrgs2uprl"/><path class="w1zi5hbum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-value-duocolor-sharp" /></template>
<style>
.jrgs2uprl {
  stroke-opacity: 0.4;
  d: path("M14 9h4v4m0-4l-6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w1zi5hbum {
  d: path("M3 5h18v14H3Zm3 6l2-2v6");
}

</style>
