<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtx_ldbpn"/><path class="fdyjbmsve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-swap-axes" /></template>
<style>
.fdyjbmsve {
  d: path("m9.5 2.5l-2 2l2 2m8 8l2 2l2-2");
}

.mtx_ldbpn {
  d: path("M3.5 3v17.5H21M7.5 4.5c6.5 0 12 5.5 12 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
