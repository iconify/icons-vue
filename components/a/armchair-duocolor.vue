<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xbb-2oo3o"/><path class="b_a_ofb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-duocolor" /></template>
<style>
.b_a_ofb4e {
  d: path("M4 11v5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-5a2 2 0 1 0-4 0a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 7v2m12-2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xbb-2oo3o {
  stroke-opacity: 0.4;
  d: path("M6 9V6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v3");
}

</style>
