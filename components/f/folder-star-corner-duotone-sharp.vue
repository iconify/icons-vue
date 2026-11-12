<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dw5c2ithy"/><path class="pud708bqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-star-corner-duotone-sharp" /></template>
<style>
.dw5c2ithy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 3h7c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m14 10.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

.ft5dv1b6b {
  fill: none;
}

.pud708bqn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h9v2M8 20H3V4h7l2 2m5 7.4l1.2 2.4l2.8.4l-2 2l.4 2.4l-2.4-1.2l-2.4 1.2l.4-2.4l-2-2l2.8-.4Z");
}

</style>
