<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl48ckbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crane-building-sharp" /></template>
<style>
.fl48ckbbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.25V2.75M2.75 5.5h18.5M3.5 21.25h4m2.75-5.75h11v5.75h-11zm3 2.75h1.5m2.25 0h1.5m-1-12.75v4m-2 0h4v3h-4z");
}

</style>
