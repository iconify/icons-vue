<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h4r7x6mwj"/><path class="s4i9qqr5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-right-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h4r7x6mwj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Zm4 10a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3Z");
}

.s4i9qqr5y {
  d: path("M21 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

</style>
