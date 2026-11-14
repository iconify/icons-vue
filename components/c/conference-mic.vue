<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdmphbb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:conference-mic" /></template>
<style>
.vdmphbb9v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21c0-2.5 2-3.5 4.5-3.5s4.5 1 4.5 3.5ZM9 17.5V14c0-3.25 2-5.25 5.25-5.5m3.737-6.212l2.475 2.475l-4.949 4.949l-2.475-2.475Z");
}

</style>
