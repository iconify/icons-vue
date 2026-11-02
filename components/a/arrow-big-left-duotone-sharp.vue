<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r7j3gobfg"/><path class="fxxci7bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-left-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fxxci7bul {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12V9h-8V4l-8 8l8 8v-5h8z");
}

.r7j3gobfg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 9v6h-8v5l-8-8l8-8v5Z");
}

</style>
