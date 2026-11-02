<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2axkab4k"/><path class="y1innc7rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-text-bulk-round" /></template>
<style>
.a2axkab4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.y1innc7rh {
  d: path("M15 10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>
