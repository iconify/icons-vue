<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjlkgjbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:list-tree" /></template>
<style>
.cjlkgjbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h.01m3.99 0h12m-8 7.5h8m-8 6.5h8M4.5 8v8A2.5 2.5 0 0 0 7 18.5h2M4.5 12H9");
}

</style>
