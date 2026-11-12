<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k39kknjgm"/><path class="gmv1bpeop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-pump-duocolor-sharp" /></template>
<style>
.gmv1bpeop {
  d: path("M3 3h18v16H3Zm4 16v2m10-2v2");
}

.k39kknjgm {
  stroke-opacity: 0.4;
  d: path("M7 11a5 5 0 0 1 10 0m0 0a5 5 0 0 1-10 0m5 0c-2 0-2-5 0-5m0 5c0-2 5-2 5 0m-5 0c2 0 2 5 0 5m0-5c0 2-5 2-5 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
