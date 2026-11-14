<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjbgotbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gender-pay-gap" /></template>
<style>
.fjbgotbrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.75h7v2.75h-7ZM3 14h7v2.75H3Zm-.5-2.75h7V14h-7ZM3 8.5h7v2.75H3Zm-.5-2.75h7V8.5h-7Zm11.5 11h7v2.75h-7Zm.5-2.75h7v2.75h-7ZM16 5.75h3.5m-1.75 0v5.5m-1.75 0h3.5");
}

</style>
