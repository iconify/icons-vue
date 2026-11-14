<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnjyvuldq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:black-friday" /></template>
<style>
.pnjyvuldq {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7l4 4v15h-15v-15Zm3.5 1a2.5 2.5 0 1 0 0 5a2.5 2.5 0 1 0 0-5m-3.75 6.75a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 1 0 0-4.5m7.5 5.5a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 1 0 0-4.5m1.5-3.5l-2-2l-8.5 8.5l2 2Z");
}

</style>
