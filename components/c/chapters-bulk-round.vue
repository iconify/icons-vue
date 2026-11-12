<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q-ww95bmn"/><path class="vsh7ybcqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chapters-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q-ww95bmn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.vsh7ybcqf {
  d: path("M9 14V6a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 14m-6 6h3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m7 0h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2");
}

</style>
