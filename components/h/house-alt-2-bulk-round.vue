<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a6b8w9bpo"/><path class="gt71-xrst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-bulk-round" /></template>
<style>
.a6b8w9bpo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 13c0-1.317.335-2.748 1.293-3.707l3-3a5.243 5.243 0 0 1 7.414 0l3 3C19.665 10.252 20 11.683 20 13v7a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm10 3a2 2 0 1 0-4 0v4h4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gt71-xrst {
  d: path("M3 21a1 1 0 0 1 0-2h6v-3a3 3 0 1 1 6 0v3h6a1 1 0 0 1 0 2Zm10-2v-3a1 1 0 0 0-2 0v3Z");
}

</style>
