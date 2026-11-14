<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dox90ab-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handwriting" /></template>
<style>
.dox90ab-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5C6 20.5 6.5 14 9 14s1.5 5 4 5c2 0 2.5-3 4-3.5c1-.25 2 .5 3.5.5M17.252 4.752l1.89 1.89a1.5 1.5 0 0 1-.289 2.346l-5.63 3.378a1.5 1.5 0 0 1-.478.185l-.995.199a.85.85 0 0 1-1-1l.187-.934a1.5 1.5 0 0 1 .25-.578l3.784-5.297a1.5 1.5 0 0 1 2.281-.189");
}

</style>
