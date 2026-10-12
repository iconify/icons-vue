<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9r6lebzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crop-rotate" /></template>
<style>
.a9r6lebzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75v12.5a1 1 0 0 0 1 1h13.5m-18.5-9.5h9.5a1 1 0 0 1 1 1v13.5M15 3.5a4.75 4.75 0 0 1 4.75 4.75m-1.5-1.5l1.5 1.5l1.5-1.5");
}

</style>
