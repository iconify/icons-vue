<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rag2m6mlt"/><path class="m2udfcc4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cigarette-off-fill" /></template>
<style>
.m2udfcc4z {
  d: path("M10.151 4.4942C10.6341 3.9557 11.25 3.5301 11.9609 3.2714M16 3C17.6569 3 19 4.3431 19 6L19 7.5C20.6569 7.5 22 8.8431 22 10.5L22 12M19 7.5L17.5 7.5M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rag2m6mlt {
  fill: currentColor;
  d: path("M19 19L19 20.5C19 21.3284 18.3284 22 17.5 22L3.5 22C2.1193 22 1 20.8807 1 19.5L1 17.5C1 16.1193 2.1193 15 3.5 15L15 15L19 19Z");
  stroke: none;
}

</style>
