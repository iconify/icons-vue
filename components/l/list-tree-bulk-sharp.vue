<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c0ry7d0of"/><path class="d0983y84f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-tree-bulk-sharp" /></template>
<style>
.c0ry7d0of {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 11h3a1 1 0 0 1 0 2H5v4h3a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V6a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d0983y84f {
  d: path("M20 5a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
