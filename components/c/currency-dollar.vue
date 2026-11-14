<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4_o-u_ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:currency-dollar" /></template>
<style>
.e4_o-u_ka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 7.75C15.6 6.1 14 5 12 5C9.6 5 8 6.4 8 8.5c0 4.75 8 2.25 8 7.25c0 2-1.75 3.25-4 3.25s-3.75-1.1-4.25-2.75m3-13.25v2m2.5-2v2m-2.5 14v2m2.5-2v2");
}

</style>
