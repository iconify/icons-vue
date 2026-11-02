<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d0vykxf0y"/><path class="ev2ql0b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:charging-station-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d0vykxf0y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.ev2ql0b1m {
  d: path("M13 11h4a1 1 0 0 1 1 1v4h2V7.414l-2.707-2.707a.999.999 0 1 1 1.414-1.414l3 3A1 1 0 0 1 22 7v10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4h-3a1 1 0 0 1 0-2M9.8 8.6L8 11h2a.998.998 0 0 1 .8 1.6l-3 4a1 1 0 0 1-1.6-1.2L8 13H6a.998.998 0 0 1-.8-1.6l3-4a1 1 0 0 1 1.6 1.2");
}

</style>
