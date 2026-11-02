<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d85anezlk"/><path class="mnz9i0n8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-duotone-sharp" /></template>
<style>
.d85anezlk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20 10l-4 2v4c0 1.105-1.791 2-4 2s-4-.895-4-2v-4l-4-2l8-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.mnz9i0n8m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l8 4l-8 4l-8-4zm-4 6v4c0 1.105 1.79 2 4 2s4-.895 4-2v-4m4-2v5");
}

</style>
