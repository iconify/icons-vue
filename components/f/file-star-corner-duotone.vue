<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y14xo4qyi"/><path class="omkihybhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-star-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.omkihybhl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H7a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h2m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-2 4.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

.y14xo4qyi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 11v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1m3-7v2a2 2 0 0 0 2 2h2Zm4 9.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

</style>
