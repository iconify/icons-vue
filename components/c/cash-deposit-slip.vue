<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sbo-yn2nd"/><path class="wqlsylt0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-deposit-slip" /></template>
<style>
.sbo-yn2nd {
  d: path("M15.2 21.5H5v-19h14v9.7M8 6h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqlsylt0s {
  d: path("M15.2 12.5H8V9h8v3.2M8 16h4m6-1v6m-3-3h6");
}

</style>
