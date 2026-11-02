<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="um-8nqbwo"/><path class="n7z4b6otw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-click-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.n7z4b6otw {
  d: path("M8 3a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0Zm5.293.293a.999.999 0 1 1 1.414 1.414l-1 1a.999.999 0 1 1-1.414-1.414ZM3 10a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2Zm1.707 4.707a.999.999 0 1 1-1.414-1.414l1-1a.999.999 0 1 1 1.414 1.414Z");
}

.um-8nqbwo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l.751.751a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-.751-.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265");
}

</style>
