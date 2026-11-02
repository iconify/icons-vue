<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nz10urdjl"/><path class="h89mikgff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folders-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h89mikgff {
  d: path("M6 5v-.001A3 3 0 0 1 9 2h3c.265 0 .52.105.707.293L14.414 4H17a5 5 0 0 1 5 5v6a1 1 0 0 1-2 0V9a3.004 3.004 0 0 0-3-3h-3a1 1 0 0 1-.707-.293L11.586 4H9a1 1 0 0 0-1 1a1 1 0 0 1-2 0");
}

.nz10urdjl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.707 8.293L10.414 10H13a5 5 0 0 1 5 5v2a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-6a3 3 0 0 1 3-3h3c.265 0 .52.105.707.293");
}

</style>
