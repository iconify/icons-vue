<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-zb_80cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bells-multiple" /></template>
<style>
.a-zb_80cf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 10.5a4.5 4.5 0 0 1 9 0V14l1.25 2c.25.5 0 1-.5 1H4.25c-.5 0-.75-.5-.5-1L5 14Zm4.5-6.75V6m6-2A4.5 4.5 0 0 1 20 8.5V12l1.25 2c.25.5 0 1-.5 1H18M8 20h3");
}

</style>
