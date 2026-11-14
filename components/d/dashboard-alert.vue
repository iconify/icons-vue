<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mpkc7bcsc"/><path class="wqx0u-b-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-alert" /></template>
<style>
.mpkc7bcsc {
  d: path("M10.8 21.5H2.5v-19h19v12.2M2.5 11h13.9m3.2 0h1.9M11 11v10.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqx0u-b-b {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m0 8.5l4 7.5h-8Zm0 3.25v1M18 20h.01");
}

</style>
