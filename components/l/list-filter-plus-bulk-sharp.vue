<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wkdh-696c"/><path class="uttof_bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-filter-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uttof_bop {
  d: path("M11 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm6 9H7a1 1 0 0 1 0-2h10a1 1 0 0 1 0 2m-3 7h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

.wkdh-696c {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0V7h-2a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0Z");
}

</style>
