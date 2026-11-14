<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ddg-bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chanterelle" /></template>
<style>
.x4ddg-bdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8q1-3.5 4-2.25q2-2.75 5-1q3-2 5.5 0Q20.5 4 21.5 6.5c-3 2-5.75 3.5-6.75 7c-.5 2 0 4.5.25 6a1.75 1.75 0 0 1-1.75 2H11A1.5 1.5 0 0 1 9.5 20c.25-2.5.25-4.5-.25-6.25c-1-3-3.75-4.5-6.75-5.75m9.5.25V12");
}

</style>
