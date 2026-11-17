<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rbfc9qb_d"/><path class="z45q14lze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:footprints-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rbfc9qb_d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 19h-5v-5c0-3-2-4-2-7c0-2 1-4 4-4c2 0 3 1 3 4ZM3 21V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v5Z");
}

.z45q14lze {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17V9c0-3 1-4 3-4c3 0 4 2 4 4c0 3-2 4-2 7v5H3zm18-2V7c0-3-1-4-3-4c-3 0-4 2-4 4c0 3 2 4 2 7v5h5zM3 17h5m13-2h-5");
}

</style>
