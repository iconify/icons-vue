<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bi4b6bcql"/><path class="ft6s3wbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-duocolor-round" /></template>
<style>
.bi4b6bcql {
  stroke-opacity: 0.4;
  d: path("M7 5a2 2 0 0 1 2-2h3l2 2m0 0h3a4 4 0 0 1 4 4v6");
}

.ft6s3wbhe {
  d: path("M10 11h3a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-6a2 2 0 0 1 2-2h3z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
