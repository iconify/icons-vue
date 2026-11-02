<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qx2-4wb0y"/><path class="lr-jwabpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lr-jwabpa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3h14v14M3 7h14v14H3Zm0 10l5-5l4 4l2-2l3 3");
}

.qx2-4wb0y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h14v14H3Z");
}

</style>
