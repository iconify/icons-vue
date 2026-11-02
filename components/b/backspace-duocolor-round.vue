<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yagfc6xce"/><path class="ssxoxxb0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ssxoxxb0s {
  d: path("M15 6h2a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-7c-.64 0-1.36-.36-2-1l-4-4a1.414 1.414 0 0 1 0-2l4-4c.64-.64 1.36-1 2-1z");
}

.yagfc6xce {
  stroke-opacity: 0.4;
  d: path("m13 10l4 4m0-4l-4 4");
}

</style>
