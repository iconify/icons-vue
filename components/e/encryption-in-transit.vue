<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llp9z19xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:encryption-in-transit" /></template>
<style>
.llp9z19xg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.688 10.5h2.625a2.19 2.19 0 0 1 2.187 2.188v1.625a2.19 2.19 0 0 1-2.187 2.187h-2.625A2.19 2.19 0 0 1 8.5 14.313v-1.625a2.19 2.19 0 0 1 2.188-2.188m-.688 0v-1a2 2 0 0 1 4 0v1m-11.5 3H6m-2-2l2 2l-2 2m14-2h3.5m-2-2l2 2l-2 2");
}

</style>
