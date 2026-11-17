<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gp9k5p8mf"/><path class="yffi_koea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eagle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gp9k5p8mf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 6c1.763-2.026 4.35-2.999 7-3c3.499.002 5.998 2.501 6 6v11l-3-2l-2 3l-2-4l-3 3c0-2.464-.495-4.992-2-7H5c-.598 0-1 .402-1 1c-.82-.704-1-1.982-1-3c.002-2.998 2.002-4.998 5-5");
}

.yffi_koea {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6c2-2.3 4.8-3 7-3c3.5 0 6 2.5 6 6v11l-3-2l-2 3l-2-4l-3 3c0-2.5-.5-5-2-7H5c-.6 0-1 .4-1 1c-.7-.6-1-1.7-1-3c0-3 2-5 5-5m4 3h.01");
}

</style>
