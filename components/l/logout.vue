<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhfu8clfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:logout" /></template>
<style>
.jhfu8clfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 6V4.5a2 2 0 0 0-2-2H5.5a2 2 0 0 0-2 2v15a2 2 0 0 0 2 2H11a2 2 0 0 0 2-2V18m-5-6h13m-3.5-3.5L21 12l-3.5 3.5");
}

</style>
