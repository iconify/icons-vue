<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2d1g3i1b"/><path class="o516xlv3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:indent-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f2d1g3i1b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.586 12L3.293 8.707a.999.999 0 1 1 1.414-1.414l4 4a1 1 0 0 1 0 1.414l-4 4a.999.999 0 1 1-1.414-1.414Z");
}

.o516xlv3h {
  d: path("M20 5a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
