<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afh6hpbaf"/><path class="erdp6sbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-number-light" /></template>
<style>
.afh6hpbaf {
  d: path("M10.875 2.5h2.25A4.375 4.375 0 0 1 17.5 6.875v.75A4.375 4.375 0 0 1 13.125 12h-2.25A4.375 4.375 0 0 1 6.5 7.625v-.75A4.375 4.375 0 0 1 10.875 2.5M12 12.5V21m-4 0h8");
}

.erdp6sbut {
  d: path("M10.25 5.5c.25-.75 1-1 1.75-1c1 0 1.75.5 1.75 1.25S13 7 12.25 7c1 0 1.75.5 1.75 1.5c0 .75-.75 1.25-2 1.25c-.75 0-1.5-.25-1.75-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
