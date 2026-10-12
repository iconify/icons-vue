<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kbbodlbzf"/><path class="i-yradg8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fortune-cookie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-yradg8r {
  d: path("M12 7.25c-.75 1.75-.75 3.5 0 4.5m0 .75l4.5 7.5");
}

.kbbodlbzf {
  d: path("M3 13c0-4.5 4-7.75 9-7.75S21 8.5 21 13c0 1.4-1.25 2.4-2.6 1.9L12 12.5l-6.4 2.4C4.25 15.4 3 14.4 3 13");
}

</style>
