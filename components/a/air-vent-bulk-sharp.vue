<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d0vykxf0y"/><path class="yd_g28bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d0vykxf0y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.yd_g28bbg {
  d: path("M7 17a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0ZM21 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
