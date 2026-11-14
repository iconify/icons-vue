<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftvgzb9fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-delivery-desk" /></template>
<style>
.ftvgzb9fa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.9 13H2.5v-2.5h15.3m.4 0h3.3V13h-.4m-9.7 7H4v-7h10.9M3 21.5h8.4m-5.9-17h8v6h-8Zm4 0V7m8.5 7l3.75 3.25v4.5h-7.5v-4.5Zm0 7.75v-2.5");
}

</style>
