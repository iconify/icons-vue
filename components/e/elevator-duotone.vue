<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m_928u62u"/><path class="j7ewb3rdf"/><path class="isy2lrdil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:elevator-duotone" /></template>
<style>
.isy2lrdil {
  fill: currentColor;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

.j7ewb3rdf {
  d: path("M6 12H8M8 12H10M8 12V13M8 13L6 17M8 13L10 17M20 3V21M22 5L20 3L18 5M22 19L20 21L18 19");
}

.m_928u62u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 12L15 18C15 20.2092 13.2092 22 11 22L5 22C2.7908 22 1 20.2092 1 18L1 6C1 3.7908 2.7908 2 5 2L11 2C13.2092 2 15 3.7908 15 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
