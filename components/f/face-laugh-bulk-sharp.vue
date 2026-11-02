<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="hi6-uy0ui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-laugh-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hi6-uy0ui {
  d: path("M9.01 8a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2ZM15 8h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2m-7 4h8a1 1 0 0 1 1 1a5 5 0 0 1-1.464 3.536A4.98 4.98 0 0 1 12 18a4.98 4.98 0 0 1-3.536-1.464A5 5 0 0 1 7 13a1 1 0 0 1 1-1");
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
