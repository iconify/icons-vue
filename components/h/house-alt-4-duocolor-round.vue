<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uczsy5j1o"/><path class="rjq5kibim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-4-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjq5kibim {
  d: path("m3 11l6.343-5.638a4 4 0 0 1 5.314 0L21 11m-2-1.778V17a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9.222");
}

.uczsy5j1o {
  stroke-opacity: 0.4;
  d: path("M12 17h-1a2 2 0 0 1-2-2v-2.435a2 2 0 0 1 .671-1.495l1-.889a2 2 0 0 1 2.658 0l1 .889A2 2 0 0 1 15 12.565V15a2 2 0 0 1-2 2z");
}

</style>
