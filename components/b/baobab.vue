<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tae8--b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baobab" /></template>
<style>
.tae8--b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 21.25c-1-3.75-.75-7.25 1.75-10c.25-.5.25-1 .25-1.75h3.5c0 .75 0 1.25.25 1.75c2.5 2.75 2.75 6.25 1.75 10Zm2.5-11.75l-5.5-3.25m5.5 3.25l-1.5-5.75m4 5.75l5.5-3.25m-5.5 3.25l1.5-5.75m-12 2.5h4.5m0-2.5H11m2 0h3.75m0 2.5h4.5");
}

</style>
