<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e_zwlabjj"/><path class="z5tqv4v5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:framer-duotone-sharp" /></template>
<style>
.e_zwlabjj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 3h12v6h-6Zm6 12v6l-6-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.z5tqv4v5d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9L6 3h12v6zm-6 6h6v6Zm6-6l6 6H6V9m0 0h6");
}

</style>
