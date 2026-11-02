<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dcvx-qzrl"/><path class="y76rj4t7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:grid-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dcvx-qzrl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.y76rj4t7k {
  d: path("M10 8h4V4a1 1 0 0 1 2 0v4h4a1 1 0 0 1 0 2h-4v4h4a1 1 0 0 1 0 2h-4v4a1 1 0 0 1-2 0v-4h-4v4a1 1 0 0 1-2 0v-4H4a1 1 0 0 1 0-2h4v-4H4a1 1 0 0 1 0-2h4V4a1 1 0 0 1 2 0Zm4 2h-4v4h4Z");
}

</style>
