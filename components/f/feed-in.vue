<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_mmo16rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feed-in" /></template>
<style>
.c_mmo16rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11L5 4h7l-2.5 7Zm12 10.5l3.25-17l3.25 17m-6-13h5.5m-16.75-1h7M4 16.5h8m-2-2l2 2l-2 2");
}

</style>
