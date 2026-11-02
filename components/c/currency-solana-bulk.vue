<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ruxnuf11w"/><path class="vaoqwsymw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-solana-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ruxnuf11w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 5a1 1 0 0 1 .709 1.705l-.002.002L18.414 9H3.586l3.707-3.707l.001-.002C7.482 5.105 7.736 5 8 5ZM3 10h14.414l3.293 3.293l.002.002c.186.187.291.441.291.705H6.586l-3.295-3.294A1 1 0 0 1 3 10m2.586 5h14.828l-3.707 3.707l-.002.002A1 1 0 0 1 16 19H4a1 1 0 0 1-.709-1.705l.002-.002Z");
}

.vaoqwsymw {
  d: path("M5.5 11a1 1 0 0 1 0-2h9.25a1 1 0 0 1 0 2Zm13 2a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Z");
}

</style>
