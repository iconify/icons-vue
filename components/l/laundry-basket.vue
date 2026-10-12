<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyns-5bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laundry-basket" /></template>
<style>
.pyns-5bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5m-17 2.5h15.5L18.5 19.6a1.85 1.85 0 0 1-1.84 1.65H7.34A1.85 1.85 0 0 1 5.5 19.6Zm4.75 3v6m3-6v6m3-6v6");
}

</style>
