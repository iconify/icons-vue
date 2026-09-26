<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lg23rtbof"/><path class="tsp8w5b4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-down-two-tone" /></template>
<style>
.lg23rtbof {
  stroke-opacity: 0.4;
  d: path("M7 9L12 4L17 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tsp8w5b4l {
  d: path("M7 15L12 20L17 15");
}

</style>
