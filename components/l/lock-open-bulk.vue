<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u294wob9d"/><path class="bo_utz54r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-bulk" /></template>
<style>
.bo_utz54r {
  d: path("M8 6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0v4a1 1 0 0 1-2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.u294wob9d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 12a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
