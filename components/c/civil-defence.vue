<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0hxigbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:civil-defence" /></template>
<style>
.y0hxigbsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.283 7.526l4.994 8.804a2.625 2.625 0 0 1-2.284 3.92H7.007a2.625 2.625 0 0 1-2.284-3.92l4.994-8.804a2.625 2.625 0 0 1 4.566 0M12 9.5V14m0 3h.01");
}

</style>
