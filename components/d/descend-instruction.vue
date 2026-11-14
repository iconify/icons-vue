<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0muk9qti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:descend-instruction" /></template>
<style>
.v0muk9qti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5zA2.5 2.5 0 0 1 9 5v14a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 4 19V5a2.5 2.5 0 0 1 2.5-2.5M4 7h2.25M4 12h2.25M4 17h2.25M16 3.5v17m-3.75-3.75L16 20.5l3.75-3.75");
}

</style>
