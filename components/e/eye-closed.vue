<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvujpjc_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-closed" /></template>
<style>
.wvujpjc_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5c2.5 3.5 5.5 5 9 5s6.5-1.5 9-5m-15.5 3l-2 2.5m6-.75l-.75 3m5.75-3l.75 3m3.25-4.75l2 2.5");
}

</style>
