<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yfoifzbac"/><path class="iz1sfcctr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iz1sfcctr {
  d: path("M5 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

.yfoifzbac {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 3h6a4 4 0 0 1 0 8h-6a4 4 0 0 1 0-8m0 10h2a4 4 0 0 1 0 8h-2a4 4 0 0 1 0-8");
}

</style>
