<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpymox8um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna-gain" /></template>
<style>
.fpymox8um {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.111 13.232l2.121-2.121l5.657 5.657l-2.121 2.121ZM6 16.25v5.25M9.294 9.17a5 5 0 0 1 3.536 3.536m-2.695-6.675a8.25 8.25 0 0 1 5.834 5.834m-4.993-8.973a11.5 11.5 0 0 1 8.132 8.132");
}

</style>
