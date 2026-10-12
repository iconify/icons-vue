<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bm4u5ts5k"/><path class="dmg8vwbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-voucher-sharp" /></template>
<style>
.bm4u5ts5k {
  d: path("M2.75 5.75h18.5v12.5H2.75zm5.5 0v12.5m-5.5-7h18.5");
}

.dmg8vwbsd {
  d: path("M8.25 11.25c-.75-3-3-3.75-3-1.25c0 1.5 1.75 1.25 3 1.25c.75-3 3-3.75 3-1.25c0 1.5-1.75 1.25-3 1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
