<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xdxwepj1o"/><path class="tg2i-ny4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-checklist-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tg2i-ny4c {
  d: path("M21 5a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

.xdxwepj1o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m5 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Zm0 6l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414Zm0 6l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1 1.414-1.414Z");
}

</style>
