<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_gfbybwh"/><path class="qm98t-bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:large-print-sign" /></template>
<style>
.j_gfbybwh {
  d: path("M3 2.5h18V17H3ZM12 17v4.5");
}

.qm98t-bpr {
  d: path("m8 14l4-8.5l4 8.5m-6.75-2.5h5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
