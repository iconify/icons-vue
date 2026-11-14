<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tah-m-b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beer-cheers" /></template>
<style>
.tah-m-b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.592 6.795l3.18.853a1.75 1.75 0 0 1 1.209 2.239l-2.988 9.035a1.75 1.75 0 0 1-2.115 1.141l-2.121-.569a1.75 1.75 0 0 1-1.261-2.045l1.93-9.318a1.75 1.75 0 0 1 2.166-1.336m7.636.853l3.18-.853a1.75 1.75 0 0 1 2.166 1.336l1.93 9.318a1.75 1.75 0 0 1-1.261 2.045l-2.121.569a1.75 1.75 0 0 1-2.115-1.141l-2.988-9.035a1.75 1.75 0 0 1 1.209-2.239M12 2.5v2m-3-.75L9.75 5M15 3.75L14.25 5");
}

</style>
