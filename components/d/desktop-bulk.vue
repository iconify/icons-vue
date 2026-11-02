<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x9qbi2awd"/><path class="gueq_2bnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:desktop-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gueq_2bnr {
  d: path("M4 12h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m5 7h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.x9qbi2awd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
