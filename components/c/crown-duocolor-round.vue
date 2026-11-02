<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mnafb_b5y"/><path class="gg5o0ubru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crown-duocolor-round" /></template>
<style>
.gg5o0ubru {
  d: path("m12 4l4 6l5-4l-1.403 7.716A4 4 0 0 1 15.662 17H8.338a4 4 0 0 1-3.935-3.284L3 6l5 4z");
}

.mnafb_b5y {
  stroke-opacity: 0.4;
  d: path("M5 21h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
