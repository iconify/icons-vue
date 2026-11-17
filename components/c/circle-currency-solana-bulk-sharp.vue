<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="a7jlyqb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-currency-solana-bulk-sharp" /></template>
<style>
.a7jlyqb1i {
  d: path("M15 6a1.002 1.002 0 0 1 .707 1.707l-1 1A1 1 0 0 1 14 9H9a1.002 1.002 0 0 1-.707-1.707l1-1A1 1 0 0 1 10 6Zm-1 4c.265 0 .52.105.707.293l2 2A1 1 0 0 1 16 14h-6a1 1 0 0 1-.707-.293l-2-2A1 1 0 0 1 8 10Zm-4 5h5a1.002 1.002 0 0 1 .707 1.707l-1 1A1 1 0 0 1 14 18H9a1.002 1.002 0 0 1-.707-1.707l1-1A1 1 0 0 1 10 15");
}

.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
