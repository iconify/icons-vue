<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxgyhpofw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concert-crowd-lights" /></template>
<style>
.nxgyhpofw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 9h8v12.5H8Zm3 9h2M12 2.5V6M6 3.5l1.75 2.75M18 3.5l-1.75 2.75");
}

</style>
