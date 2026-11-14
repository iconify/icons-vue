<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbd5_xqyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arch-ogee" /></template>
<style>
.gbd5_xqyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21v-9c0-3 3-3.5 4.5-5.5c.75-1 1.5-2.25 1.5-3.5c0 1.25.75 2.5 1.5 3.5C15 8.5 18 9 18 12v9M3 21h18");
}

</style>
