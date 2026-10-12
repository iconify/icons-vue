<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul2nxib4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checkout-sharp" /></template>
<style>
.ul2nxib4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h12.5v14H2.75zm3.25 0V6a3 3 0 0 1 6 0v1.25m-2.25 7h11.5m-3-3l3 3l-3 3");
}

</style>
