<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="vik5_vrvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-bitcoin-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.vik5_vrvw {
  d: path("M10 11h2a1 1 0 0 0 0-2h-2Zm-2 1V7a1 1 0 0 1 2 0h2a1 1 0 0 1 2 0v.763a3 3 0 0 1 .616 3.708A3 3 0 0 1 14 16.829V17a1 1 0 0 1-2 0h-2a1 1 0 0 1-2 0Zm2 3h3a1 1 0 0 0 0-2h-3Z");
}

</style>
