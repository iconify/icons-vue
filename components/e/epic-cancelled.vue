<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhd5q_hgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:epic-cancelled" /></template>
<style>
.zhd5q_hgn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.932 5.227l-4.081 4.802A1.5 1.5 0 0 0 5.994 12.5h1.468a1.5 1.5 0 0 1 1.477 1.761L8.5 16.75a1.015 1.015 0 0 0 1.815.779l4.167-5.637A1.5 1.5 0 0 0 13.276 9.5h-1.671a1.5 1.5 0 0 1-1.466-1.814L10.5 6a.901.901 0 0 0-1.568-.773M15.5 15.5l5 5m0-5l-5 5");
}

</style>
