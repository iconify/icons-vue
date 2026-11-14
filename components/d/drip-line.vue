<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p59fsblvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drip-line" /></template>
<style>
.p59fsblvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h19m-16.75 4s-2.25 4-2.25 6.75a2.25 2.25 0 0 0 4.5 0C7 13.5 4.75 9.5 4.75 9.5Zm7.25 0s-2.25 4-2.25 6.75a2.25 2.25 0 0 0 4.5 0C14.25 13.5 12 9.5 12 9.5Zm7.25 0S17 13.5 17 16.25a2.25 2.25 0 0 0 4.5 0c0-2.75-2.25-6.75-2.25-6.75Z");
}

</style>
