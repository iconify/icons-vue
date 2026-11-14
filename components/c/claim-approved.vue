<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c49aqubbr"/><path class="ns_iwm8ci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-approved" /></template>
<style>
.c49aqubbr {
  d: path("M11.6 19H3V2.5h13v13.1");
}

.ns_iwm8ci {
  d: path("M5.5 9.5c0-2.5 1.75-4 4-4s4 1.5 4 4Zm4 0V12c0 .75-.5 1.25-1.25 1.25S7 12.75 7 12m-1 4h6.5m2 2l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
