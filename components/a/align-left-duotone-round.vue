<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fdtj7lfgs"/><path class="b9dflnb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-duotone-round" /></template>
<style>
.b9dflnb9w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6h-6a3 3 0 0 1-3-3m0 10a3 3 0 0 1 3-3h2a3 3 0 0 1 0 6h-2a3 3 0 0 1-3-3M4 3v18");
}

.fdtj7lfgs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 4h6a3 3 0 1 1 0 6h-6a3 3 0 1 1 0-6m0 10h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6");
}

.ft5dv1b6b {
  fill: none;
}

</style>
