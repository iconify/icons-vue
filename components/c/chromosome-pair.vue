<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqonfwtwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chromosome-pair" /></template>
<style>
.dqonfwtwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3c1.5 0 2.5 1 2.5 2.5v4q0 1.5-1 2.5q1 1 1 2.5v4C9.5 20 8.5 21 7 21s-2.5-1-2.5-2.5v-4q0-1.5 1-2.5q-1-1-1-2.5v-4C4.5 4 5.5 3 7 3Zm10 0c1.5 0 2.5 1 2.5 2.5v4q0 1.5-1 2.5q1 1 1 2.5v4c0 1.5-1 2.5-2.5 2.5s-2.5-1-2.5-2.5v-4q0-1.5 1-2.5q-1-1-1-2.5v-4C14.5 4 15.5 3 17 3Zm-8.5 9h7");
}

</style>
