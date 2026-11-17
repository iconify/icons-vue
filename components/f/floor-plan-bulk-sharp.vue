<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="td1bzxb2d"/><path class="bowdlyb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:floor-plan-bulk-sharp" /></template>
<style>
.bowdlyb0b {
  d: path("M14 9a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-5 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm5 9a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.td1bzxb2d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
