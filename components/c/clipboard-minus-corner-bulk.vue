<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3rmv9bld"/><path class="bcpt4-c5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-minus-corner-bulk" /></template>
<style>
.bcpt4-c5z {
  d: path("M10 2h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2m3 13h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l3rmv9bld {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1");
}

</style>
