<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="usr9unc6p"/><path class="x3sflacnk"/><path class="p937wxhzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idea-bulb-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p937wxhzi {
  d: path("M10 21h4");
}

.usr9unc6p {
  d: path("M8 12a6 6 0 1 1 8 0v3H8Z");
}

.x3sflacnk {
  d: path("M9 18h6");
}

</style>
