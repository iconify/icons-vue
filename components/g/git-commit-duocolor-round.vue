<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q7i8brbqj"/><path class="ppdzzsb6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-commit-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ppdzzsb6b {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.q7i8brbqj {
  stroke-opacity: 0.4;
  d: path("M3 12h7m4 0h7");
}

</style>
