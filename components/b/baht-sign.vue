<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6zp_j49j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baht-sign" /></template>
<style>
.u6zp_j49j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12H13a3.75 3.75 0 0 0 0-7.5H7.5v15H14a3.75 3.75 0 0 0 0-7.5m-3-9.5v19");
}

</style>
