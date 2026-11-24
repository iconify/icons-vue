<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b3o8aj64t"/><path class="tp9nqccpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:download-duocolor" /></template>
<style>
.b3o8aj64t {
  stroke-opacity: 0.4;
  d: path("M4 16v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tp9nqccpz {
  d: path("m8 12l4 4l4-4m-4 4V4");
}

</style>
