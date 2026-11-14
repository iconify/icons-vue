<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prffgbbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arbitrage" /></template>
<style>
.prffgbbzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4a8 8 0 0 1 7.75 6.5m1.5-1.75l-1.5 1.75L18 9.25M19 16a8 8 0 0 1-9.75 3.5m1 2l-1-2l2-1M5 16A8 8 0 0 1 6.75 6m-2-.25l2 .25v2m1.75 4a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
