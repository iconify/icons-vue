<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nzgde0fvs"/><path class="n0gxl6brm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n0gxl6brm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16m-2 9a2.828 2.828 0 1 1-4-4a2.828 2.828 0 0 1 4 4m0 0l3 3");
}

.nzgde0fvs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9v12H4V9Z");
}

</style>
