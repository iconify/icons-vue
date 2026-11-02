<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m86gzebtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal" /></template>
<style>
.m86gzebtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3h7a2 2 0 0 1 2 2v4h5a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2v4a2 2 0 0 1-2 2H4zm0 6h9m-9 6h12");
}

</style>
