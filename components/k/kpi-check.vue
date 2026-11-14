<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="inpkuyb1e"/><path class="nx6ux2lcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kpi-check" /></template>
<style>
.inpkuyb1e {
  d: path("M13.6 21H2.5V3h19v8.8m0 7.9V21h-1.2M6 6.75h5");
}

.nx6ux2lcz {
  d: path("M7.5 15.5v-6l-3 4h4m.75-2.25a1.75 1.75 0 0 1 3.5 0c0 1.75-3.5 2.5-3.5 4.25h3.5M14.5 18l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
