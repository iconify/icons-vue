<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="atg5p_aof"/><path class="ac7_phb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-bulk-sharp" /></template>
<style>
.ac7_phb1z {
  d: path("M2 8V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-3v2h16V5Zm10 8h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

.atg5p_aof {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V9H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
