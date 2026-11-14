<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svr2dzb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-course" /></template>
<style>
.svr2dzb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5V19m2.027-14.74l2.228.836a1.5 1.5 0 0 1 0 2.808l-2.228.836A1.5 1.5 0 0 1 9 7.335v-1.67a1.5 1.5 0 0 1 2.027-1.405M3.5 20.5c2.5-2 8.5-2 11 0");
}

</style>
