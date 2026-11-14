<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztq2rbb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bust-statue" /></template>
<style>
.ztq2rbb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3 10c0-3 2.5-4.5 5.5-4.5s5.5 1.5 5.5 4.5Zm2.671 0h5.658a1.5 1.5 0 0 1 1.455 1.136l.75 3a1.5 1.5 0 0 1-1.455 1.864H8.421a1.5 1.5 0 0 1-1.455-1.864l.75-3A1.5 1.5 0 0 1 9.171 15.5");
}

</style>
