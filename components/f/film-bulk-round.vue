<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="ijbwaabdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:film-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ijbwaabdg {
  d: path("M8 8v3h8V3a1 1 0 0 1 2 0v4h3a1 1 0 0 1 0 2h-3v2h3a1 1 0 0 1 0 2h-3v2h3a1 1 0 0 1 0 2h-3v4a1 1 0 0 1-2 0v-8H8v8a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2h3v-2H3a1 1 0 0 1 0-2h3V9H3a1 1 0 0 1 0-2h3V3a1 1 0 0 1 2 0Z");
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
