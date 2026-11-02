<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lag8zcrrd"/><path class="cngxt-90p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-duocolor-sharp" /></template>
<style>
.cngxt-90p {
  d: path("m13 8l-3 3h4l-3 3");
}

.lag8zcrrd {
  stroke-opacity: 0.4;
  d: path("M4 18v-8l3-6h10l3 6v8zm2 0h2v2H6Zm10 0h2v2h-2ZM3 10h1m16 0h1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
