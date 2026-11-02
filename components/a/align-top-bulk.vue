<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="odhzi4b9f"/><path class="n4vwsnj3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n4vwsnj3k {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

.odhzi4b9f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3m10 0h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>
