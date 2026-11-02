<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uv9i6gbdr"/><path class="v7m2oq_5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drag-vertical-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.uv9i6gbdr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 7a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-6 6a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-6 6a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

.v7m2oq_5b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
