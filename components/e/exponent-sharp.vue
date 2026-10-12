<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxwnv6bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:exponent-sharp" /></template>
<style>
.dxwnv6bka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 9.25l8.75 11m0-11l-8.75 11m11.5-14.5l.4-2h4.6v3.5L19 8.5L15.25 12h5");
}

</style>
