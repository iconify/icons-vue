<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-o_s5blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-pump" /></template>
<style>
.z-o_s5blw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6h4v15h-4ZM4 3h11M9.5 3v3m-5 15H14M11.5 8.5c5.5 0 7 3.5 7 8.5M17 17h3v4h-3Z");
}

</style>
