<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hd10qab4k"/><path class="h390lingn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h390lingn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H7l-4 4V3h18v6m-4 7c-1-2-4-2-4 0s4 4 4 4s4-2 4-4s-3-2-4 0");
}

.hd10qab4k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9v8H7l-4 4V3h18v6Zm8 7c1-2 4-2 4 0s-4 4-4 4s-4-2-4-4s3-2 4 0");
}

</style>
