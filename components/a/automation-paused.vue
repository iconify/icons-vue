<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r-2r28rix"/><path class="vvn-nvb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation-paused" /></template>
<style>
.r-2r28rix {
  d: path("M15.429 15.022L13.5 14.25l-1.5 1l-.25 2.5h-3.5L8 15.25l-1.5-1l-2.5 1l-1.5-2.75l2-1.5V9l-2-1.5L4 4.75l2.5 1l1.5-1l.25-2.5h3.5l.25 2.5l1.5 1l2.5-1l1.5 2.75l-2 1.5v2l2 1.5l-.501.919");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvn-nvb1j {
  d: path("M7.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm11 6.25v5.5m3-5.5v5.5");
}

</style>
