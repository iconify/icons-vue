<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1mht8w_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-club-head" /></template>
<style>
.e1mht8w_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.75 2.5l-4 11.5m0 0l1 5.25c.25 1.5-.75 2.25-2.25 2.25H7.25C5 21.5 4 20 4.5 18c.5-1.75 2-2.75 3.75-2.75Zm-7.5 4.5h5.5");
}

</style>
