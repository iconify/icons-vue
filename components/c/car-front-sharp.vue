<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl9vs1bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-front-sharp" /></template>
<style>
.rl9vs1bzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13v-1h1.6L7 7.15l.438-1.394L8.9 5.75h6.2l1.462.006L17 7.15L18.65 12h1.6v7H3.75v-1Zm2.75 6v2m11-2v2m-12-9h13M6.25 15.25H8.5m7 0h2.25m-7.25 0h3");
}

</style>
