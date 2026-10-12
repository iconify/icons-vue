<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onfic2bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:enlarger-sharp" /></template>
<style>
.onfic2bph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.25h11v6h-11zm11 3h3.5m0-3.5v15.5M7 11.75L5.5 15.5m3.75-3.75v3.75m2.25-3.75L13 15.5M2.75 18.25h18.5v3H2.75z");
}

</style>
