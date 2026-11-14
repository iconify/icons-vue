<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ldufbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drill-pipe" /></template>
<style>
.u_ldufbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5H10V3h4v2h7.5v5H14v1.75h-4V10H2.5Zm9.5 9.5c1.5 1.75 2.75 3 2.75 4.25a2.75 2.75 0 0 1-5.5 0c0-1.25 1.25-2.5 2.75-4.25Z");
}

</style>
