<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aujp6vbqv"/><path class="g5ofzr94s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bird-duotone" /></template>
<style>
.aujp6vbqv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 8l3-2c0-1 1-2 3-2s3 1 4 3c1 3 4 6 8 8l-4 1c-1.169 2.334-3.558 2.999-6 3c-2.998-.002-4.998-2.002-5-5v-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.g5ofzr94s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 8l3-2c0-1 1-2 3-2s3 1 4 3c1 3 4 6 8 8l-4 1q-1.5 3-6 3c-3 0-5-2-5-5v-4Zm7 11v2m4-2v2M9 7h.01m.99 4c0 2 1 3 2 3");
}

</style>
