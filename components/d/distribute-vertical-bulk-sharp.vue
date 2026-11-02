<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ajm53ku0m"/><path class="x0p8qfbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-bulk-sharp" /></template>
<style>
.ajm53ku0m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 15V9a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.x0p8qfbfb {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 16h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
