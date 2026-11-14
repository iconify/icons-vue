<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n63ieqb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-month-age" /></template>
<style>
.n63ieqb1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12h7.5a1.75 1.75 0 0 1 1.75 1.75v5.5A1.75 1.75 0 0 1 11.75 21h-7.5a1.75 1.75 0 0 1-1.75-1.75v-5.5A1.75 1.75 0 0 1 4.25 12m3.323-8.334l3.913.832a1.75 1.75 0 0 1 1.348 2.075l-.832 3.913a1.75 1.75 0 0 1-2.075 1.348l-3.913-.832a1.75 1.75 0 0 1-1.348-2.075l.832-3.913a1.75 1.75 0 0 1 2.075-1.348M16.5 16l2-1.5V21m-2 0h4");
}

</style>
