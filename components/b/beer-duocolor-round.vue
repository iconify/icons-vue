<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p9dxmcbhl"/><path class="p4-k1v6ee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:beer-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4-k1v6ee {
  d: path("M4 9v8a4 4 0 0 0 4 4h4a4 4 0 0 0 4-4V9m0 3h1a3 3 0 0 1 0 6h-1m-8-5v4m4-4v4");
}

.p9dxmcbhl {
  stroke-opacity: 0.4;
  d: path("M4 9c-2.667-4 3.333-8 6-4c2.667-4 8.667 0 6 4z");
}

</style>
