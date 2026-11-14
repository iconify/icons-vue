<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uykogrl1p"/><path class="aqpx8mbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:horizon-level" /></template>
<style>
.aqpx8mbxp {
  d: path("M8 10.25h8v3.5H8ZM12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uykogrl1p {
  d: path("M2.5 7.5h19v9h-19Z");
}

</style>
