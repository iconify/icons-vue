<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fkt_lqmph"/><path class="uxcbxlily"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:directions-transit" /></template>
<style>
.fkt_lqmph {
  d: path("M4.5 2.5h15v16h-15Zm3 16v3m9-3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uxcbxlily {
  d: path("M7.5 5.5h9v6h-9Zm.75 9.5h.01m7.49 0h.01");
}

</style>
