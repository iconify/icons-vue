<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scksqtbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:classroom-layout" /></template>
<style>
.scksqtbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 3h7.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-7.5A1.75 1.75 0 0 1 6.5 4.75A1.75 1.75 0 0 1 8.25 3m-3 8h3A1.75 1.75 0 0 1 10 12.75a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 5.25 11m10.5 0h3a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 14 12.75A1.75 1.75 0 0 1 15.75 11m-10.5 6.5h3A1.75 1.75 0 0 1 10 19.25A1.75 1.75 0 0 1 8.25 21h-3a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75m10.5 0h3a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 18.75 21h-3A1.75 1.75 0 0 1 14 19.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
