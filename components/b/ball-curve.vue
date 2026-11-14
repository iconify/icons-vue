<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tohn-abhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-curve" /></template>
<style>
.tohn-abhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM2.5 21c7.5-.5 1.5-8 7-9");
}

</style>
