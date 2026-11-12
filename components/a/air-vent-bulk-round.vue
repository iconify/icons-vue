<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k-r8gbbdj"/><path class="yd_g28bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k-r8gbbdj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5Z");
}

.yd_g28bbg {
  d: path("M7 17a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0ZM21 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
