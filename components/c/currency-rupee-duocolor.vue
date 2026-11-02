<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5dhe1bml"/><path class="eh8r7jx3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-rupee-duocolor" /></template>
<style>
.eh8r7jx3o {
  d: path("M6 5h12M6 5h4a4 4 0 1 1 0 8H6l6 6");
}

.i5dhe1bml {
  stroke-opacity: 0.4;
  d: path("M6 9h8m0 0h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
