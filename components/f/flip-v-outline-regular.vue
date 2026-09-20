<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g2i9ptb4h"/><path class="sxlwlmkmh"/><path class="j_lyr1ori"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flip-v-outline-regular" /></template>
<style>
.g2i9ptb4h {
  d: path("m6 3 6 6 6 -6Z");
}

.j_lyr1ori {
  d: path("m6 21 6 -6 6 6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

</style>
