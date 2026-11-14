<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de4xlbc_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crossing-beacon" /></template>
<style>
.de4xlbc_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 5v9m-3.5 0h7M4.75 3.5a8.25 8.25 0 0 0 0 8m14.5-8a8.25 8.25 0 0 1 0 8");
}

</style>
