<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zywy-e6ly"/><path class="ge1hs79-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drop-shadow-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ge1hs79-x {
  d: path("M20 19V7a1 1 0 0 1 2 0v12a3 3 0 0 1-3 3H7a1 1 0 0 1 0-2h12a1 1 0 0 0 1-1");
}

.zywy-e6ly {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
