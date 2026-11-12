<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="ak6j-absg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circuit-board-bulk-round" /></template>
<style>
.ak6j-absg {
  d: path("M10 9a1 1 0 1 0-2 0a1 1 0 0 0 2 0m3-1a3 3 0 0 0 3-3V3a1 1 0 0 1 2 0v2a5 5 0 0 1-5 5h-1.171a3 3 0 1 1 0-2Zm-.829 8H11a3 3 0 0 0-3 3v2a1 1 0 0 1-2 0v-2a5 5 0 0 1 5-5h1.171a3 3 0 1 1 0 2M14 15a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
