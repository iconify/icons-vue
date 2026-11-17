<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l7fbq4dzt"/><path class="pnrm4gbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fence-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l7fbq4dzt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21V7l2-4l2 4v14Zm10 0V7l2-4l2 4v14Z");
}

.pnrm4gbhg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 21V7l2-4l2 4v14zm10 0V7l2-4l2 4v14zM3 10h2m4 0h6m4 0h2M3 16h2m4 0h6m4 0h2");
}

</style>
