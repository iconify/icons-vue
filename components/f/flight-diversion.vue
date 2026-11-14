<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvnh20b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flight-diversion" /></template>
<style>
.uvnh20b3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5V13q0-5.5 5.5-5.5h3.25m8.75 0c0 .75-.75 1-1.5 1h-2.25l-2.5 4h-1.5l1.5-4h-.75l-1 1.25h-.75v-4.5h.75l1 1.25h.75l-1.5-4h1.5l2.5 4H20c.75 0 1.5.25 1.5 1ZM4 5.5h.01M4 2.75h.01");
}

</style>
