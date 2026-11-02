<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aiwokebrf"/><path class="sc-ep82on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-bulk" /></template>
<style>
.aiwokebrf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 6a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2Zm10 0a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2v1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sc-ep82on {
  d: path("M9 13a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2Z");
}

</style>
