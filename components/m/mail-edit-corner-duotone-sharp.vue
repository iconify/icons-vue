<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x64n-hb5o"/><path class="wf8-v6ewi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-edit-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wf8-v6ewi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19H3V5h18v6M3 5l6 6h6l6-6m-7 16v-3l4-4l3 3l-4 4Z");
}

.x64n-hb5o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5h18v6H10v8H3Zm11 16v-3l4-4l3 3l-4 4Z");
}

</style>
