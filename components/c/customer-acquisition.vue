<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehng_1bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-acquisition" /></template>
<style>
.ehng_1bvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3.5 21v-1.5c0-3 3-5 7-5c1.444 0 2.758.261 3.847.735M18 15v6m-3-3h6");
}

</style>
