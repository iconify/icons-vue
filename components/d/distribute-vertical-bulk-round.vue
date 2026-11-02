<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kjay6hbhu"/><path class="x0p8qfbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kjay6hbhu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 8h6a4 4 0 0 1 0 8H9a4 4 0 0 1 0-8");
}

.x0p8qfbfb {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 16h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
