<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sa5p77ufe"/><path class="y4tx-xbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-4-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sa5p77ufe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 14h2V9a1 1 0 0 1 2 0v5h1a1 1 0 0 1 0 2h-1v3a1 1 0 0 1-2 0v-3h-3a1 1 0 0 1-1-1V9a1 1 0 0 1 2 0Z");
}

.y4tx-xbdi {
  d: path("M4 11h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
