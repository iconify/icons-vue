<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6p1_bbdp"/><path class="tyfapy8bb"/><path class="n42bz5bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-peak" /></template>
<style>
.n42bz5bcq {
  d: path("M12 7V2.5m-2 2l2-2l2 2");
}

.s6p1_bbdp {
  d: path("m2.5 20.5l4.5-3l5-7l5 7l4.5 3");
}

.tyfapy8bb {
  fill: currentColor;
  d: path("M10 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
