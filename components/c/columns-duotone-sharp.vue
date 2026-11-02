<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ojig8ib4r"/><path class="etojbffjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:columns-duotone-sharp" /></template>
<style>
.etojbffjv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h6v16H4Zm10 0h6v16h-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.ojig8ib4r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4v16H4V4Zm10 0v16h-6V4Z");
}

</style>
