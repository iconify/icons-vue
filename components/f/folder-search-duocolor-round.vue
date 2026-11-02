<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkd3r2g0j"/><path class="osfl_dbub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-search-duocolor-round" /></template>
<style>
.lkd3r2g0j {
  stroke-opacity: 0.4;
  d: path("M9 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osfl_dbub {
  d: path("M12 6h5a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5z");
}

</style>
