<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gur0pvb_o"/><path class="x949k2mzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:daylight-lamp" /></template>
<style>
.gur0pvb_o {
  d: path("M3.5 21h8m-4 0l-2.75-8.5L13.5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x949k2mzr {
  d: path("M12 9.5a5 5 0 0 1 10 0Zm1.5 2.75l-1.25 2.25m4.75-2v3m3.5-3.25l1.25 2.25");
}

</style>
