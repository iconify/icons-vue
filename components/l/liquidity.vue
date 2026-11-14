<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ic7n19bbn"/><path class="pnqlkccwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liquidity" /></template>
<style>
.ic7n19bbn {
  d: path("M12 2.75S5 10 5 14.5a7 7 0 0 0 14 0c0-4.5-7-11.75-7-11.75Z");
}

.pnqlkccwh {
  d: path("M13.75 12.5c-.25-.75-.85-1.25-1.75-1.25c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M12 10v1.25m0 6v1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
