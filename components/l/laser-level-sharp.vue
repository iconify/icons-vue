<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuk7gpbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:laser-level-sharp" /></template>
<style>
.fuk7gpbxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h10v7.5h-10zM7 8.75h3M8.5 12.5V17M5 20.25L8.5 17l3.5 3.25m3.25-11.5h2.25m2 0h1.75");
}

</style>
