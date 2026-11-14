<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lexu06blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kidswear-department" /></template>
<style>
.lexu06blu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11l1 10.5h-5L12 17l-1.5 4.5h-5Zm3.75-5.5h3.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 13.75 11h-3.5A1.75 1.75 0 0 1 8.5 9.25v-2a1.75 1.75 0 0 1 1.75-1.75m-1.75 0L7 2.5m8.5 3l1.5-3m-6.5 5.75h3");
}

</style>
