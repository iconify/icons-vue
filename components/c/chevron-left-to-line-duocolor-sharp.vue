<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbg4my0kw"/><path class="dqdgtqyjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-to-line-duocolor-sharp" /></template>
<style>
.dqdgtqyjs {
  d: path("m17 6l-6 6l6 6");
}

.fbg4my0kw {
  stroke-opacity: 0.4;
  d: path("M7 6v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
