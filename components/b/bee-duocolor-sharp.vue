<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6t2uhbxh"/><path class="rgizpj_4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bee-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6t2uhbxh {
  stroke-opacity: 0.4;
  d: path("M10 12c0-5 2-8 5-8c1.7 0 3 1 3 2c0 2.5-4 3-4 6");
}

.rgizpj_4j {
  d: path("M8 12h6c3 0 4.5 2 6 4c-1.5 2-3 4-6 4H8c-2.2 0-4-1.8-4-4s1.8-4 4-4m2 0v8m4-8v8m-7-4h.01");
}

</style>
