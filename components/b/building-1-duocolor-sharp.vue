<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lor2vm6cu"/><path class="y8brb3-1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-duocolor-sharp" /></template>
<style>
.lor2vm6cu {
  stroke-opacity: 0.4;
  d: path("M12 10.6V4H5v16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y8brb3-1p {
  d: path("M3 20h18M9 20v-7l5-4l5 4v7");
}

</style>
