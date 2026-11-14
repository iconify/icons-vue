<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw5d38b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chef-jacket" /></template>
<style>
.zw5d38b2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5L12 7l3.5-3.5l5.5 3l-1.5 5.5l-2.5-1v9.5H7V11l-2.5 1L3 6.5Zm3.5 8h.01m-.01 4h.01");
}

</style>
