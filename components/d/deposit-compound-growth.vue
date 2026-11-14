<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3mwsfb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-compound-growth" /></template>
<style>
.n3mwsfb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.25h5V21h-5ZM3 15.5h5v2.75H3Zm6.5 2.75h5V21h-5ZM9 15.5h5v2.75H9Zm.5-2.75h5v2.75h-5Zm7 5.5h5V21h-5ZM16 15.5h5v2.75h-5Zm.5-2.75h5v2.75h-5ZM16 10h5v2.75h-5Zm.5-2.75h5V10h-5Z");
}

</style>
