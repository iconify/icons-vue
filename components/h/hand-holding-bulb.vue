<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhw5l7bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-holding-bulb" /></template>
<style>
.dhw5l7bhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 11c-1.5-1-2.5-2.5-2.5-4.5a4.5 4.5 0 0 1 9 0c0 2-1 3.5-2.5 4.5Zm-7.5 7h3l3 3.5h7l5-4.5c.75-.75 0-2-1-1.5l-3.75 3H11.5m-1.5-5h4M10.75 16h2.5");
}

</style>
