<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rkp-lm7ed"/><path class="n5iafhovj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-edit-duocolor-sharp" /></template>
<style>
.n5iafhovj {
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkp-lm7ed {
  stroke-opacity: 0.4;
  d: path("M8 16v-3l5-5l3 3l-5 5Z");
}

</style>
