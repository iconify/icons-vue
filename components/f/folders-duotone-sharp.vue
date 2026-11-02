<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rju3wmbbo"/><path class="ha3jr9b3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ha3jr9b3i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 11h7v10H3V9h5zM7 5V3h5l2 2m0 0h7v10");
}

.rju3wmbbo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 8c.265 0 .52.105.707.293L10.414 10H17a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Z");
}

</style>
