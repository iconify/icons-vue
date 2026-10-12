<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qle87-rkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:evaporating-dish-sharp" /></template>
<style>
.qle87-rkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11.5h18c0 2.25-3.75 3.5-8.5 3.5s-7.5-1.25-8-2.75Zm2 6.5h14.5M7 18l-1.5 3.25M17 18l1.5 3.25M9.5 8.5c-.9-1.2.9-2.2 0-3.75m5 3.75c-.9-1.2.9-2.2 0-3.75");
}

</style>
