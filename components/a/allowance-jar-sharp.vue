<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w18ej_bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:allowance-jar-sharp" /></template>
<style>
.w18ej_bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6a2.5 2.5 0 0 1 5 0ZM7.75 6h8.5v2.5h-8.5zm-2.5 5.5h13.5v9.75H5.25z");
}

</style>
