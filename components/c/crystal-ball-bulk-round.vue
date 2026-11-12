<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e4g61-bar"/><path class="wmp6jj3dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crystal-ball-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4g61-bar {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 22H7a3 3 0 0 1-1.821-5.385c-2.076-2.424-2.623-5.717-1.554-8.713a8.893 8.893 0 0 1 15.538-2.299a9.2 9.2 0 0 1 1.731 4.845a8.63 8.63 0 0 1-2.073 6.167A3.002 3.002 0 0 1 17 22");
}

.wmp6jj3dr {
  d: path("M8.315 8.443c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 12 6a1 1 0 0 1 0 2c-.533 0-1.039.207-1.414.586A1.98 1.98 0 0 0 10 10a1 1 0 0 1-2 0a4 4 0 0 1 .315-1.557M19 18H5a1 1 0 0 1 0-2h14a1 1 0 0 1 0 2");
}

</style>
