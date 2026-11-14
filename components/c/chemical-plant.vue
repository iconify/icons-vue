<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8xozm7jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemical-plant" /></template>
<style>
.z8xozm7jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21V7a3.5 3.5 0 0 1 7 0v14m3 0V10a3.5 3.5 0 0 1 7 0v11m-18 0h19m-11-7h3");
}

</style>
