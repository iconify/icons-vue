<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lksy91b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:list-alpha" /></template>
<style>
.lksy91b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6.5h9.5M11 15h9.5m-17-7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M7.5 5v4.25m-4 2.25V17m0-2a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
