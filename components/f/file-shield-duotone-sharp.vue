<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y5cezzoxv"/><path class="nbep6c-jl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nbep6c-jl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6m-7 3h3v2c0 2-1 3-3 4c-2-1-3-2-3-4v-2z");
}

.y5cezzoxv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Z");
}

</style>
