<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxra9ac4k"/><path class="n4vwsnj3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lxra9ac4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm10 0a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1Z");
}

.n4vwsnj3k {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
