<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s-35n8b_t"/><path class="deev6eljl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:beer-duotone-round" /></template>
<style>
.deev6eljl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9v8a4 4 0 0 0 4 4h4a4 4 0 0 0 4-4V9m0 3h1a3 3 0 0 1 0 6h-1m-8-5v4m4-4v4M4 9c-2.667-4 3.333-8 6-4c2.667-4 8.667 0 6 4z");
}

.ft5dv1b6b {
  fill: none;
}

.s-35n8b_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9c-2.661-4.004 3.327-7.996 6-4c2.673-3.996 8.661-.004 6 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Z");
}

</style>
