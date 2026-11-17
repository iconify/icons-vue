<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_439rg-f"/><path class="qgdb25rzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:faucet-duotone-sharp" /></template>
<style>
.b_439rg-f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6h18v6h-4v-2H3Zm16 10c1 1 2 2 2 3a2 2 0 1 1-4 0c0-1 1-2 2-3");
}

.ft5dv1b6b {
  fill: none;
}

.qgdb25rzh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h18v6h-4v-2H3zm0-2v8m4-9h6m-3 0v3m11 13a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

</style>
