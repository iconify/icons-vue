<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u5u1subrl"/><path class="o8-e-_blr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:behance-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8-e-_blr {
  d: path("M15 13h6a3 3 0 0 0-6 0v2a3 3 0 0 0 3 3c1 0 1.6-.4 2-1M16 6h4");
}

.u5u1subrl {
  stroke-opacity: 0.4;
  d: path("M3 18V6h3a3 3 0 0 1 0 6H3m0 0h4a3 3 0 0 1 0 6H3");
}

</style>
