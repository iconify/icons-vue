<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f9znh2twl"/><path class="jeke5b99r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:columns-duotone-round" /></template>
<style>
.f9znh2twl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 7v10a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0m10 0v10a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0");
}

.ft5dv1b6b {
  fill: none;
}

.jeke5b99r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Zm10 0a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Z");
}

</style>
