<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0wju_ygz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cinema-screen-sharp" /></template>
<style>
.q0wju_ygz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h2.5c0 5.5.5 11 1.75 16.5H2.75Zm18.5 0h-2.5c0 5.5-.5 11-1.75 16.5h4.25Zm-16 0h13.5m-10 4h6.5v4.5h-6.5z");
}

</style>
