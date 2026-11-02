<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygqlu6xwg"/><path class="ca-ggxbuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:contacts-bulk" /></template>
<style>
.ca-ggxbuz {
  d: path("M8 10a4 4 0 1 1 8 0a4 4 0 0 1-8 0m11-1a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2Zm-9 1a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m9 7a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2ZM7 21a5 5 0 0 1 10 0a1 1 0 0 1-2 0a3 3 0 1 0-6 0a1 1 0 0 1-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ygqlu6xwg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
