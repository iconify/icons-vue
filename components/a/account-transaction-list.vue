<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h58g-0bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-transaction-list" /></template>
<style>
.h58g-0bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h5m-2-2l2 2l-2 2m2 7.5h-5m2-2l-2 2l2 2m6-11.5H16m3 0h2.5m-11 9.5H16m3 0h2.5m-1.25-1.25v2.5");
}

</style>
