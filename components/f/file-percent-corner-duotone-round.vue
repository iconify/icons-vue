<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u-feg9-iu"/><path class="cjzp5wesp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-percent-corner-duotone-round" /></template>
<style>
.cjzp5wesp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m1 5l-6 6m-1-6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.u-feg9-iu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13 3l.034.034q-.01-.01-.022-.004a.02.02 0 0 0-.012.018V7c0 1.103.897 1.998 2 2h-2a4 4 0 0 0-4 4v8a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4Z");
}

</style>
