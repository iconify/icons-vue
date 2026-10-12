<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za7r1acil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hoverboard" /></template>
<style>
.za7r1acil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.04 11.75H10v-.5q0-.5.5-.5h3q.5 0 .5.5v.5h2.96a2.5 2.5 0 1 1 0 3.5H7.04a2.5 2.5 0 1 1 0-3.5");
}

</style>
