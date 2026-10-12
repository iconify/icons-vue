<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-91dobnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cupcake" /></template>
<style>
.p-91dobnf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.25A2.25 2.25 0 0 1 6.25 6a5.75 3.25 0 0 1 11.5 0a2.25 2.25 0 0 1 1.5 4.25Zm.25 2.5h14l-1.5 7.5a1.25 1.25 0 0 1-1.25 1h-8.5a1.25 1.25 0 0 1-1.25-1Zm4.5 2.5l.25 3.5m4.75-3.5l-.25 3.5");
}

</style>
