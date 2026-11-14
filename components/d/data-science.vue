<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhioi_1et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-science" /></template>
<style>
.jhioi_1et {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.9 15.5H4.5v-11h15v5.4m-17 8.6h8.4m-3.65-6.25v-2m2.75 2V9m2.75 3.25V7.5m2.5 6l-2 3.5l2 3.5m3.5-7l2 3.5l-2 3.5");
}

</style>
