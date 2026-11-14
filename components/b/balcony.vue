<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l_6ybun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balcony" /></template>
<style>
.k_l_6ybun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13V4a1.5 1.5 0 0 1 1.5-1.5h7A1.5 1.5 0 0 1 17 4v9M2.5 13h19m-19 8.5h19M14.75 9h.01M7 13v8.5m5-8.5v8.5m5-8.5v8.5");
}

</style>
