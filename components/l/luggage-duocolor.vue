<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e53frpbez"/><path class="f8o4zsb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-duocolor" /></template>
<style>
.e53frpbez {
  stroke-opacity: 0.4;
  d: path("M7 19a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

.f8o4zsb2v {
  d: path("M7 19a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2m-6 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
