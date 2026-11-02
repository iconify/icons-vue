<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pcg59_y6d"/><path class="k2kjdac-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-info-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k2kjdac-x {
  d: path("M12 7h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2m1 4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

.pcg59_y6d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 17.707l-4 4a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0l8 8a2.414 2.414 0 0 1 0 3.414Z");
}

</style>
