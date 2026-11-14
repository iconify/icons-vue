<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3bnnkbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb-spot" /></template>
<style>
.t3bnnkbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 11.5V9.25a3.5 3.5 0 1 1 3 0v2.25m-4.75 0h6.5l4.75 4H4ZM6.5 18.25L5 21.5m7-3.25v3.25m5.5-3.25L19 21.5");
}

</style>
