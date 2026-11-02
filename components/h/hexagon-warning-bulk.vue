<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z7pcgrb_q"/><path class="x8h2cnb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-warning-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.x8h2cnb6m {
  d: path("M13 9v4a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

.z7pcgrb_q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 8.236v7.528a3 3 0 0 1-1.658 2.683l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236");
}

</style>
