<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v4yamjb7g"/><path class="htvxiz1vk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chain-scan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htvxiz1vk {
  d: path("M7 9.25L12 12l5-2.75M12 12v5.5");
}

.v4yamjb7g {
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m9.223-9.102l3.5 1.925A1.5 1.5 0 0 1 17 10.137v3.726a1.5 1.5 0 0 1-.777 1.314l-3.5 1.925a1.5 1.5 0 0 1-1.446 0l-3.5-1.925A1.5 1.5 0 0 1 7 13.863v-3.726a1.5 1.5 0 0 1 .777-1.314l3.5-1.925a1.5 1.5 0 0 1 1.446 0");
}

</style>
