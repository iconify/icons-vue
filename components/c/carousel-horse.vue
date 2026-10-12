<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fuhnxfjrp"/><path class="rogigf1zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carousel-horse" /></template>
<style>
.fuhnxfjrp {
  d: path("M12 2.75V10m0 7.25v4M5.5 12.5C5.5 11 6.75 10 8.25 10h6.5L17 6.5c.5-.75 1.5-1 2.25-.5l1.5 1c.5.4.6 1 .25 1.5l-.75 1l-1.5-.5L17 12.25v2.25c0 1.5-1.25 2.75-2.75 2.75h-6c-1.5 0-2.75-1.25-2.75-2.75Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rogigf1zk {
  d: path("M8 17.25L6.75 21m8-4.75L17 17.5l-.5 2.25m-11-8.25c-1.5 0-2.5 1-2.75 2.5");
}

</style>
