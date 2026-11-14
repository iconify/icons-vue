<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xsr7bbc0d"/><path class="d3d1g9q-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-coin-machine" /></template>
<style>
.d3d1g9q-g {
  d: path("M11.7 11H7V5h10v5.7M6.5 13.75h5.2m-4.95 3.5h.01m2.49 0h.01M14.25 19h6.5v2.75h-6.5Zm1.25-2.75h6.25V19H15.5Zm-1-2.75h6.25v2.75H14.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsr7bbc0d {
  d: path("M11.4 21.5H4v-19h16v8.2");
}

</style>
