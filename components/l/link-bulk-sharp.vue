<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h_ko-vmap"/><path class="jo979gbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:link-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h_ko-vmap {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.293 7.293a.999.999 0 1 1 1.414 1.414l-8 8a.999.999 0 1 1-1.414-1.414Z");
}

.jo979gbts {
  d: path("M18.293 10.293a3.243 3.243 0 0 0-4.586-4.586l-2 2a.999.999 0 1 1-1.414-1.414l2-2a5.243 5.243 0 0 1 7.414 7.414l-2 2a.999.999 0 1 1-1.414-1.414ZM5.707 13.707a3.243 3.243 0 0 0 4.586 4.586l2-2a.999.999 0 1 1 1.414 1.414l-2 2a5.243 5.243 0 0 1-7.414-7.414l2-2a.999.999 0 1 1 1.414 1.414Z");
}

</style>
