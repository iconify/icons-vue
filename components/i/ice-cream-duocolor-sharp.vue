<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nugocvbqd"/><path class="futcg5bwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ice-cream-duocolor-sharp" /></template>
<style>
.futcg5bwj {
  d: path("M7 8a5 5 0 0 1 10 0a2 2 0 1 1 0 4H7a2 2 0 1 1 0-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nugocvbqd {
  stroke-opacity: 0.4;
  d: path("m7 12l5 9l5-9");
}

</style>
