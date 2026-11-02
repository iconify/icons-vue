<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r31-m1inr"/><path class="kg5_lfr6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ghost-duocolor" /></template>
<style>
.kg5_lfr6o {
  d: path("M4 11a8 8 0 1 1 16 0v8c0 .738-.631 1.369-1 1l-1-1a2.83 2.83 0 0 0-4 0a2.83 2.83 0 0 1-4 0a2.83 2.83 0 0 0-4 0l-1 1c-.369.369-1-.262-1-1z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r31-m1inr {
  stroke-opacity: 0.4;
  d: path("M9 10h.01M15 10h.01");
}

</style>
