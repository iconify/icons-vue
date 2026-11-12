<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ziwln3kxj"/><path class="fx9gftn8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-pin-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fx9gftn8x {
  d: path("M20 12a1 1 0 0 1 0 2v1.586l1.707 1.707A1 1 0 0 1 21 19h-3v2a1 1 0 0 1-2 0v-2h-3a1.002 1.002 0 0 1-.707-1.707L14 15.586V14a1 1 0 0 1 0-2Z");
}

.ziwln3kxj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h7c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
