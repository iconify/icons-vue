<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="mhn0dj8tr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mhn0dj8tr {
  d: path("M10 9a1 1 0 1 0-2 0a1 1 0 0 0 2 0m5-1a1 1 0 0 0 1-1V3a1 1 0 0 1 2 0v4a3 3 0 0 1-3 3h-3.171a3 3 0 1 1 0-2Zm-2.829 8H9a1 1 0 0 0-1 1v4a1 1 0 0 1-2 0v-4a3 3 0 0 1 3-3h3.171a3 3 0 1 1 0 2M14 15a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
