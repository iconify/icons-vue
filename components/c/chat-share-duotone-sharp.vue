<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wpkkbtb6t"/><path class="vbydadeae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-share-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vbydadeae {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H7l-4 4V3h18v14zm-4-4v-3h8m-3-3l3 3l-3 3");
}

.wpkkbtb6t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1Z");
}

</style>
