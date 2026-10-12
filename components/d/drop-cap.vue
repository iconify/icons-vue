<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6x1t8i8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drop-cap" /></template>
<style>
.f6x1t8i8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 4.75h6.75M13.5 9.5h6.75m-6.75 4.75h6.75m-16.5 5h16.5m-17-4.75L6.75 4l3.5 10.5m-5.7-4h4.4");
}

</style>
