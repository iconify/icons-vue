<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yb09diboz"/><path class="zz1cu7bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.yb09diboz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 5h6a4 4 0 0 1 4 4v7a2 2 0 0 1-2 2h-3a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732H5a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4");
}

.zz1cu7bvo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18H5a2 2 0 0 1-2-2V9a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v7a2 2 0 0 1-2 2h-3m-5-8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1Zm1 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9-3h4");
}

</style>
