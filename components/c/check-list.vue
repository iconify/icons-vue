<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj5leab2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:check-list" /></template>
<style>
.vj5leab2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 6l1.75 1.75L8 4.5M3 13l1.75 1.75L8 11.5M11 6h10m-10 7h10M4.75 17.5h1a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 3 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m6.25 2h10");
}

</style>
