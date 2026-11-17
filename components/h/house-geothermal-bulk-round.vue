<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vrshizwmh"/><path class="hk815eb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-geothermal-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hk815eb9i {
  d: path("M13 16v2h5a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1h5v-2H9.667a4 4 0 0 1-4-4V9.028a4 4 0 0 1 1.366-3.01l2.333-2.042a4 4 0 0 1 5.268 0l2.333 2.042a4 4 0 0 1 1.366 3.01V12a4 4 0 0 1-4 4Zm-1-2h2.333a2 2 0 0 0 2-2V9.028a2 2 0 0 0-.683-1.505l-2.333-2.042a2 2 0 0 0-2.634 0L8.35 7.523a2 2 0 0 0-.683 1.505V12a2 2 0 0 0 2 2Z");
}

.vrshizwmh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.333 16H9.667a4 4 0 0 1-4-4V9.028a4 4 0 0 1 1.366-3.01l2.333-2.042a4 4 0 0 1 5.268 0l2.333 2.042a4 4 0 0 1 1.366 3.01V12a4 4 0 0 1-4 4");
}

</style>
