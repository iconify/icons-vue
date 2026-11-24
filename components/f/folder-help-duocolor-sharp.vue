<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a2d4gor6c"/><path class="og2hi81sh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-duocolor-sharp" /></template>
<style>
.a2d4gor6c {
  stroke-opacity: 0.4;
  d: path("M10 12a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.og2hi81sh {
  d: path("M12 6h9v14H3V4h7z");
}

</style>
