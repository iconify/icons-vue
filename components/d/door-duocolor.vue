<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n93wedc1i"/><path class="askyiccey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-duocolor" /></template>
<style>
.askyiccey {
  d: path("M3 21h18M6 21V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v16");
}

.n93wedc1i {
  stroke-opacity: 0.4;
  d: path("M14 12h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
