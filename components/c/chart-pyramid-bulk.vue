<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a-vlnry1x"/><path class="j4qh7cpvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pyramid-bulk" /></template>
<style>
.a-vlnry1x {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m16.894 10.553l4 8c.181.356.274.75.273 1.149C21.164 20.924 20.265 22 19 22H5c-1.265 0-2.164-1.076-2.167-2.298a2.5 2.5 0 0 1 .273-1.149l7-14a2.116 2.116 0 0 1 3.788 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j4qh7cpvq {
  d: path("M15 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm3 6a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
