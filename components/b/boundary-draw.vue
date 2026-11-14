<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he1-g8bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boundary-draw" /></template>
<style>
.he1-g8bdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.349 5H9.83a1.75 1.75 0 0 1 1.713 1.389l1.263 6a1.75 1.75 0 0 1-1.713 2.111H4.77a1.75 1.75 0 0 1-1.692-2.195l1.579-6A1.75 1.75 0 0 1 6.349 5M16.5 18.75l-.25-3.25L19 10l3 1.5l-2.75 5.5Zm-14 0h14m-.25-3.25l3 1.5");
}

</style>
