<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ue8pbfbst"/><path class="vsh7ybcqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chapters-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ue8pbfbst {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.vsh7ybcqf {
  d: path("M9 14V6a1 1 0 0 1 1.555-.832l6 4a1 1 0 0 1 0 1.664l-6 4A1 1 0 0 1 9 14m-6 6h3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m7 0h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2m8 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2");
}

</style>
