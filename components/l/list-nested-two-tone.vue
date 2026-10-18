<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dic350bnc"/><path class="q4_xqmble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-nested-two-tone" /></template>
<style>
.dic350bnc {
  stroke-opacity: 0.4;
  d: path("M9 4.5L21 4.5M11 12L21 12M13 19.5L21 19.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q4_xqmble {
  d: path("M3 3L5 4.5L3 6ZM5 10.5L7 12L5 13.5ZM7 18L9 19.5L7 21Z");
}

</style>
