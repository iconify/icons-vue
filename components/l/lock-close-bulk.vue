<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lpcc7-b1f"/><path class="w98kbubcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-close-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lpcc7-b1f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.w98kbubcx {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-6.293 5.293L12 13.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 15l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
