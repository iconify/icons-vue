<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x5nflnusd"/><path class="j0aukbb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earth-heart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0aukbb1m {
  d: path("M12 7.5c-2.25 4-2.25 9 0 13M3.25 12h17.5");
}

.x5nflnusd {
  d: path("M12 20.5c-6-4-9.25-7.25-9.25-11.5A4.75 4.75 0 0 1 12 7.5A4.75 4.75 0 0 1 21.25 9c0 4.25-3.25 7.5-9.25 11.5");
}

</style>
