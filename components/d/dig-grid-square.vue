<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hso2fl2ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dig-grid-square" /></template>
<style>
.hso2fl2ac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.4 17.5H2.5v-15h15v10.2M7.5 2.5v15m5-15v15m-10-10h15m-15 5h15m-1 3h3m-1.5 0v2m-1.75 0h3.5V20L18 22l-1.75-2Z");
}

</style>
