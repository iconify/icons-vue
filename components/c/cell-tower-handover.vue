<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txs7gjbnm"/><path class="ohnk6ztpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-tower-handover" /></template>
<style>
.ohnk6ztpt {
  d: path("m15.25 8l2.25 1l1-2.5");
}

.txs7gjbnm {
  d: path("m3.5 21l3-9l3 9m5 0l3-9l3 9M6.5 8.5a6.5 6.5 0 0 1 11 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
