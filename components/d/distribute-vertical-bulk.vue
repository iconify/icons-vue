<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mydtzaccn"/><path class="x0p8qfbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mydtzaccn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 8h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3");
}

.x0p8qfbfb {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 16h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
