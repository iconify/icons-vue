<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpjmus8db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gantry-crane-sharp" /></template>
<style>
.gpjmus8db {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.25V4.75m16 16.5V4.75m-17.25 0h18.5m-9.25 0v3.5m-3.5 0h7v4h-7zm-1.25 7h9.5v6h-9.5zm3.25 0v6m3-6v6");
}

</style>
