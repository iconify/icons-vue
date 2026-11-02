<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tpfg9chjq"/><path class="daas2obdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:archive-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.daas2obdg {
  d: path("M5 3h14a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6m0 4h14a1 1 0 0 0 0-2H5a1 1 0 0 0 0 2m9 6h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

.tpfg9chjq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 3h14a3 3 0 0 1 1 5.829V16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 21H9a5 5 0 0 1-5-5V8.829A3.001 3.001 0 0 1 5 3");
}

</style>
