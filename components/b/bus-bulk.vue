<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p3o7egbhc"/><path class="co47idbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-bulk" /></template>
<style>
.co47idbtl {
  d: path("M9 5h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2M8 15h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p3o7egbhc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 5v12c0 1.27-.803 2.405-2 2.829V21a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1h-4v1a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-1.171A3 3 0 0 1 4 17V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3M6 5v7h12V5a1 1 0 0 0-1-1H7a1 1 0 0 0-1 1");
}

</style>
