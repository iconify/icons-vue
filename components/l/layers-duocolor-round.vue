<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hmevflb0n"/><path class="qfzrkp-wp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layers-duocolor-round" /></template>
<style>
.hmevflb0n {
  stroke-opacity: 0.4;
  d: path("m4 12l8 4l8-4M4 16l8 4l8-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qfzrkp-wp {
  d: path("m8 6l4-2l6 3a1.118 1.118 0 0 1 0 2l-6 3l-6-3a1.118 1.118 0 0 1 0-2z");
}

</style>
