<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mff6osbjl"/><path class="y9mnqqtwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mff6osbjl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 16L15 4l6 6l-10 10H7Z");
}

.y9mnqqtwa {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l6-6l-6-6l-6 6m2 10h10M9 10l6 6m-6-6l-6 6l4 4h4l4-4");
}

</style>
