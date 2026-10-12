<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tof_g1bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beret-sharp" /></template>
<style>
.tof_g1bch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5c0-3.5 4.25-6 9.5-6s9 2.25 9 5c0 2.25-2.75 3.75-5.75 4H2.75zM6 17h11v3H6zm6.25-11.5L13 2.75");
}

</style>
