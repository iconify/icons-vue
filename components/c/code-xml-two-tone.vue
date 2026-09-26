<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sfbfre4oy"/><path class="nm76pbt0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:code-xml-two-tone" /></template>
<style>
.nm76pbt0e {
  d: path("M10 19L14 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sfbfre4oy {
  stroke-opacity: 0.4;
  d: path("M6 7L2 12L6 17M18 7L22 12L18 17");
}

</style>
