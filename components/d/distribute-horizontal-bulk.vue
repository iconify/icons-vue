<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s7bzfum0x"/><path class="yu2y7hbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s7bzfum0x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 8a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3Z");
}

.yu2y7hbmc {
  d: path("M5 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m16 0v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

</style>
