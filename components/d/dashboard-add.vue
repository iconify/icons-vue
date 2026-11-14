<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u3vzycb8x"/><path class="sf6iyj5pv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-add" /></template>
<style>
.sf6iyj5pv {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m0 9v7M14.5 18h7");
}

.u3vzycb8x {
  d: path("M15.2 21.5H2.5v-19h19v12.7m0 5.6v.7h-.7M2.5 11h19M11 11v10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
