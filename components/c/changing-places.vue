<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-cg5ccne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:changing-places" /></template>
<style>
.u-cg5ccne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10V4a1.5 1.5 0 0 1 1.5-1.5H7A1.5 1.5 0 0 1 8.5 4v6m5.526 3.485c-.659.919-1.618 1.508-2.776 1.765l.5 4.75H6.5l.5-4.75c-2.5-1-4-2.75-4-5.25h12q-.001.789-.134 1.462m1.884 2.788a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm.75 2.5v1.75h2.75l1.25 2.25m-6.25-4a2.75 2.75 0 0 0 4 4");
}

</style>
