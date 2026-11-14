<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qwhe5z3ha"/><path class="p4iq38n8d"/><path class="yelp5pb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gamelan-gong" /></template>
<style>
.p4iq38n8d {
  d: path("M6.5 12.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.qwhe5z3ha {
  d: path("M3.5 20.5v-17h17v17M12 3.5V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yelp5pb9k {
  d: path("M10 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
