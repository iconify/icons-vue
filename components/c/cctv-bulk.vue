<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f99965bch"/><path class="uvv_bhb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cctv-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f99965bch {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h14a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6m3 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

.uvv_bhb9z {
  d: path("M18 14V7a1 1 0 0 1 2 0v7a8 8 0 0 1-16 0V7a1 1 0 0 1 2 0v7a6 6 0 1 0 12 0M8 14a4 4 0 1 1 8 0a4 4 0 0 1-8 0m2 0a2 2 0 1 0 3.999.001A2 2 0 0 0 10 14m2-1h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
