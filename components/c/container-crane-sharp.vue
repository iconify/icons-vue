<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdese80k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:container-crane-sharp" /></template>
<style>
.ahdese80k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.25V5m5.5 16.25V5M2.75 5h18.5M5 13l5.5-8M5 13h5.5M17 5v6m-3.25.75h6.5v4.75h-6.5zm3.25 0v4.75");
}

</style>
