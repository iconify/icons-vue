<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q1ndt2nsh"/><path class="x8h2cnb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-warning-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q1ndt2nsh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9v6c0 1.693-1.069 3.152-2.553 3.894l-4 2a5.47 5.47 0 0 1-4.894 0l-4-2C4.069 18.152 3 16.693 3 15V9c0-1.693 1.069-3.152 2.553-3.894l4-2a5.47 5.47 0 0 1 4.894 0l4 2C19.931 5.848 21 7.307 21 9");
}

.x8h2cnb6m {
  d: path("M13 9v4a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
