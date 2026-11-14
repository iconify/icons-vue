<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ergf9lcrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:holi-color-powder" /></template>
<style>
.ergf9lcrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 14.25l-7-5.5l4-5.5l7.25 5.25M3 21h18m-10 0q5-7.5 10 0m-7-7.5h.01m3.49-1h.01");
}

</style>
