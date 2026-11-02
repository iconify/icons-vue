<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xbj-e-6di"/><path class="z3vibnb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xbj-e-6di {
  stroke-opacity: 0.4;
  d: path("M7 4L6 6m5-2l-1 2m5-2l-1 2");
}

.z3vibnb9x {
  d: path("M3 13v-2a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2a7 7 0 0 1-14 0m14-3h2a2 2 0 1 1 0 4h-2");
}

</style>
