<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v2-i63btl"/><path class="p9-32ir4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p9-32ir4f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 4l2 2l-4 4l-4-4l4-4zm-6 6l2 2l-4 4l-4-4l4-4zm12 0l2 2l-4 4l-4-4l4-4zm-6 6l2 2l-4 4l-4-4l4-4z");
}

.v2-i63btl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 6l-4 4l-4-4l4-4Zm-6 6l-4 4l-4-4l4-4Zm12 0l-4 4l-4-4l4-4Zm-6 6l-4 4l-4-4l4-4Z");
}

</style>
