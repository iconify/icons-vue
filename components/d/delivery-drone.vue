<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsly7_b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-drone" /></template>
<style>
.fsly7_b0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5.5h7v4h-7Zm-3.25 2H8.5m7 0h3.25m-13.5 0V3m13.5 4.5V3M2.5 3H8m8 0h5.5M10.25 9.5V13m3.5-3.5V13M7.5 13h9v8.5h-9Zm0 3.5h9");
}

</style>
