<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izd9lacbg"/><path class="in8-iz5or"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-help-duocolor" /></template>
<style>
.in8-iz5or {
  d: path("M20 8.236v7.528a2 2 0 0 1-1.106 1.789l-6 3a2 2 0 0 1-1.788 0l-6-3A2 2 0 0 1 4 15.763V8.237a2 2 0 0 1 1.106-1.789l6-3a2 2 0 0 1 1.788 0l6 3A2 2 0 0 1 20 8.237");
}

.izd9lacbg {
  stroke-opacity: 0.4;
  d: path("M10 11a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
