<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6jxipbvu"/><path class="ab32t8bmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-duocolor-sharp" /></template>
<style>
.ab32t8bmf {
  d: path("M6 9v6h12V9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6jxipbvu {
  stroke-opacity: 0.4;
  d: path("M3 4h18M3 20h18");
}

</style>
