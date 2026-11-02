<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d51wstmpi"/><path class="c_o5l5o1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-duotone-sharp" /></template>
<style>
.c_o5l5o1s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8h14l2 12H3zm3 0a4 4 0 1 1 8 0");
}

.d51wstmpi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 7c.489 0 .906.353.986.836l2 12A.998.998 0 0 1 21 21H3a.998.998 0 0 1-.986-1.164l2-12A1 1 0 0 1 5 7Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
