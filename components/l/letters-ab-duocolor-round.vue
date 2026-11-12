<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gh1j_6b-t"/><path class="ett2-92no"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letters-ab-duocolor-round" /></template>
<style>
.ett2-92no {
  d: path("M3 18L7 6l4 12m-7-3h6");
}

.gh1j_6b-t {
  stroke-opacity: 0.4;
  d: path("M15 6v12h3a3 3 0 0 0 0-6h-3m0-6h3a3 3 0 0 1 0 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
