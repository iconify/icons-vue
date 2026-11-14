<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps20wdnpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capillary-action" /></template>
<style>
.ps20wdnpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11v8.5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V11M10.5 2.5v16m3-16v16M10.5 8q1.5 1.5 3 0M3 15h7.5m3 0H21");
}

</style>
