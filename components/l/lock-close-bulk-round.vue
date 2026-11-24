<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k__5w9oyx"/><path class="w98kbubcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-close-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k__5w9oyx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5Z");
}

.w98kbubcx {
  d: path("M17 7v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0V7a5 5 0 0 1 10 0m-6.293 5.293L12 13.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 15l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
