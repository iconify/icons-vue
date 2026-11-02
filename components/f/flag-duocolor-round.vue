<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkntuhbzi"/><path class="c5_wc7b7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-duocolor-round" /></template>
<style>
.c5_wc7b7b {
  d: path("M4 15c6-3 10 3 16 0V4C14 7 10 1 4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tkntuhbzi {
  stroke-opacity: 0.4;
  d: path("M4 15v6");
}

</style>
