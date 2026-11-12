<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rd8d7acmw"/><path class="puqbclblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-share-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.puqbclblu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-3 5h4v4m0-4l-6 6");
}

.rd8d7acmw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

</style>
