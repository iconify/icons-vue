<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7-2rzbpx"/><path class="bcky-ebks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dishwasher" /></template>
<style>
.bcky-ebks {
  d: path("M8.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM7.5 6h.01");
}

.k7-2rzbpx {
  d: path("M4 3.5h16v17H4Zm0 5h16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
