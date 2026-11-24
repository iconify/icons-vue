<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e906b4bdd"/><path class="haho3yb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-corner-duocolor" /></template>
<style>
.e906b4bdd {
  stroke-opacity: 0.4;
  d: path("M17 14v4m0 3h.01");
}

.haho3yb6z {
  d: path("M9 5H7a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h2M19 9V7a2 2 0 0 0-2-2h-2M9 5V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1M9 5v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
