<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys3elfbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coal-seam" /></template>
<style>
.ys3elfbxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21V6Q7 3.5 12 5.5t9.5-.5v16Zm0-10.5h19m-19 6h19M8 13.5h.01m3.99 0h.01m3.99 0h.01");
}

</style>
