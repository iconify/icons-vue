<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tq75yhbrq"/><path class="g55uqgb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bug-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g55uqgb3x {
  d: path("M8.315 5.443a4 4 0 0 1 4.48-2.363A4 4 0 0 1 16 7a1 1 0 0 1-2 0a2 2 0 0 0-4 0a1 1 0 0 1-2 0a4 4 0 0 1 .315-1.557M3.293 8.707a.999.999 0 1 1 1.414-1.414l3 3A1 1 0 0 1 7 12a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h4a1 1 0 0 1-.707-.293Zm13 1.586l3-3a.999.999 0 1 1 1.414 1.414l-3 3A1 1 0 0 1 17 12h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2a1.002 1.002 0 0 1-.707-1.707M13 18a1 1 0 0 1-2 0v-7a1 1 0 0 1 2 0Zm-7.293 1.707a.999.999 0 1 1-1.414-1.414l3-3a.999.999 0 1 1 1.414 1.414Zm11-4.414l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414");
}

.tq75yhbrq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.874 6H17a1 1 0 0 1 1 1v6a6 6 0 1 1-12 0V7a1 1 0 0 1 1-1h1.126a4 4 0 0 1 7.748 0");
}

</style>
