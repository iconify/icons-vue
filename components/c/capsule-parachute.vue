<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl3t0rbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:capsule-parachute" /></template>
<style>
.jl3t0rbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5c0-5 4-8 9-8s9 3 9 8Zm7 5.5h4c1.5 0 2.5 4 3 5.5H7C7.5 20 8.5 16 10 16Zm-7-5.5l7 5.5m11-5.5L14 16");
}

</style>
