<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w9d8bccze"/><path class="gt7tjcbwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fireplace-duocolor" /></template>
<style>
.gt7tjcbwu {
  d: path("M3 3h18M5 3v18M19 3v18M3 21h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w9d8bccze {
  stroke-opacity: 0.4;
  d: path("M12 6.5c.313 1.563 1.25 2.813 2.5 3.75c.938.938 1.25 2.188 1.25 3.75a3.75 3.75 0 1 1-7.5 0c0-.937.313-1.562.625-1.875m0 0a1.25 1.25 0 1 0 2.5 0c0-.937-.312-1.25-.625-1.875C10.125 9 10.438 7.75 12 6.5");
}

</style>
