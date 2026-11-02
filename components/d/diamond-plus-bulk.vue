<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pcg59_y6d"/><path class="u49e6y-wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-plus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pcg59_y6d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 17.707l-4 4a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0l8 8a2.414 2.414 0 0 1 0 3.414Z");
}

.u49e6y-wx {
  d: path("M13 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2V9a1 1 0 0 1 2 0");
}

</style>
