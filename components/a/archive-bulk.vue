<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qltr8zbjt"/><path class="daas2obdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.daas2obdg {
  d: path("M5 3h14a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6m0 4h14a1 1 0 0 0 0-2H5a1 1 0 0 0 0 2m9 6h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

.qltr8zbjt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3h14a3 3 0 0 1 1 5.829V18a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8.829A3.001 3.001 0 0 1 5 3");
}

</style>
