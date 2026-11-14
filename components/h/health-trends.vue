<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l73pdpbsu"/><path class="fksyncb1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-trends" /></template>
<style>
.fksyncb1r {
  d: path("m6 17l3-2h1.25l1-5l1.5 7.5l1-4.5L16 11.5L20.5 5");
}

.l73pdpbsu {
  d: path("M3.5 2.5v18h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
