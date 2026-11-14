<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntj7vtbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:antenna-patch" /></template>
<style>
.ntj7vtbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 5l4-1.5v11L4 16Zm2 10.25v5.25m-2.5 0h5m3.75-14a6 6 0 0 1 0 6m3-7.75a9.5 9.5 0 0 1 0 9.5m3-11.25a13 13 0 0 1 0 13");
}

</style>
