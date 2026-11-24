<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lc00r8biz"/><path class="cbgj1ir0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-corner-duotone" /></template>
<style>
.cbgj1ir0m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21H6a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2M8 9V7a4 4 0 1 1 8 0v2m-2 12v-3l4-4l3 3l-4 4Z");
}

.ft5dv1b6b {
  fill: none;
}

.lc00r8biz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 21a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h6a2 2 0 0 0-2 2v10Zm8-3l4-4l3 3l-4 4h-3Z");
}

</style>
