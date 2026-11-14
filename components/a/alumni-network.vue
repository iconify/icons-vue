<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifnaqsbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alumni-network" /></template>
<style>
.ifnaqsbxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.188 2.5h3.625A2.19 2.19 0 0 1 16 4.688v1.625A2.19 2.19 0 0 1 13.813 8.5h-3.625A2.19 2.19 0 0 1 8 6.313V4.688A2.19 2.19 0 0 1 10.188 2.5M4.688 15h3.625a2.19 2.19 0 0 1 2.187 2.188v1.625A2.19 2.19 0 0 1 8.313 21H4.688A2.19 2.19 0 0 1 2.5 18.813v-1.625A2.19 2.19 0 0 1 4.688 15m11 0h3.625a2.19 2.19 0 0 1 2.187 2.188v1.625A2.19 2.19 0 0 1 19.313 21h-3.625a2.19 2.19 0 0 1-2.188-2.187v-1.625A2.19 2.19 0 0 1 15.688 15M10.75 5.5h2.5m-8 12.5h2.5m8.5 0h2.5M9.5 8.5l-3 6.5m8-6.5l3 6.5m-7 3h3");
}

</style>
