<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydcpp-bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jellyfish-marine-sharp" /></template>
<style>
.ydcpp-bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9.5a6.25 6.25 0 0 1 12.5 0v1.25H5.75zm2.75 3.25L7.5 14l1 1.25l1 1.25l-1 1.25m3.5-5L11 14l1 1.25l1 1.25l-1 1.25m3.5-5l-1 1.25l1 1.25l1 1.25l-1 1.25m-12.75 3C4 20.75 4 20 5.25 20s1.25.75 2.5.75S9 20 10.25 20s1.25.75 2.5.75S14 20 15.25 20s1.25.75 2.5.75S19 20 20.25 20");
}

</style>
