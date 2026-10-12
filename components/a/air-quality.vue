<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbnr-9c6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:air-quality" /></template>
<style>
.hbnr-9c6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.5h7.5m-7.5 4h9m-9 4h6m4 3.5C12.5 12 16 7.5 20.5 6.25c.5 7-2.75 13.5-7.75 13.75");
}

</style>
