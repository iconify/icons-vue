<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thuerya1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:height-limit" /></template>
<style>
.thuerya1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h16m-16 17h16M12 6.25v11.5M9.75 8.5L12 6.25l2.25 2.25m-4.5 7L12 17.75l2.25-2.25");
}

</style>
