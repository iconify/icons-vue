<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeu0wac_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:harbour-limit" /></template>
<style>
.jeu0wac_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5v7m0-7l4 5h-4m-5 2h10l-1.5 3h-7Zm5-11a9.5 9.5 0 0 1 6.106 2.223m2.121 2.527a9.5 9.5 0 0 1 1.129 6.4m-1.129 3.1a9.5 9.5 0 0 1-4.978 4.177M12 21.5a9.5 9.5 0 0 1-6.106-2.223M3.773 16.75a9.5 9.5 0 0 1-1.129-6.4m1.129-3.1a9.5 9.5 0 0 1 4.978-4.177");
}

</style>
