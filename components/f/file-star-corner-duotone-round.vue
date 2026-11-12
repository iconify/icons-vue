<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rgb14hbjv"/><path class="gozodrd8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-star-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gozodrd8t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-2 4.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

.rgb14hbjv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 21a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3Zm3-17v2a2 2 0 0 0 2 2h2Zm4 9.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

</style>
