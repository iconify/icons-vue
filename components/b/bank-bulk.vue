<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m4t4_yb1z"/><path class="cjxs-8b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bank-bulk" /></template>
<style>
.cjxs-8b7m {
  d: path("M7 17a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4-6v6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0m4 6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0Zm4-6v6a1 1 0 0 1-2 0v-6a1 1 0 0 1 2 0m2 9a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.m4t4_yb1z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 8H3a1 1 0 0 1-.406-1.914l9-4a1 1 0 0 1 .812 0l9 4A1 1 0 0 1 21 8");
}

</style>
