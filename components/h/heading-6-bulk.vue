<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g5xb99jis"/><path class="y4tx-xbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-6-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g5xb99jis {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12a4 4 0 0 1 4-4h2a1 1 0 0 1 0 2h-2a2 2 0 0 0-2 2v.535A4.002 4.002 0 0 1 21.464 18A4 4 0 0 1 14 16Zm2 4a2 2 0 1 0 3.999.001A2 2 0 0 0 16 16");
}

.y4tx-xbdi {
  d: path("M4 11h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
