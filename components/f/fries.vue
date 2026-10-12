<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1wd6oi7h"/><path class="du1rbp14c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fries" /></template>
<style>
.du1rbp14c {
  d: path("M9.5 14.5c1.5 1 3.5 1 5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1wd6oi7h {
  d: path("M5 10.25h14l-1.5 9.25a2 2 0 0 1-2 1.75h-7a2 2 0 0 1-2-1.75Zm2.75 0l-.75-5m4 5V3m3 7.25L14.5 4m2.5 6.25l1-4.5");
}

</style>
