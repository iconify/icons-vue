<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x2af8ibpk"/><path class="bo_utz54r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-bulk-sharp" /></template>
<style>
.bo_utz54r {
  d: path("M8 6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0v4a1 1 0 0 1-2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.x2af8ibpk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 9h16a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1");
}

</style>
