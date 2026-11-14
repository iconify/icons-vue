<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcj4ocgei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burnout" /></template>
<style>
.hcj4ocgei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3s4.5 4.5 4.5 9.75a4.5 4.5 0 0 1-9 0C7.5 10.5 9 9 10 7.5c.5 1.75 1.25 2.25 2 2.25C12.5 7.5 12 5 12 3M5 21h14");
}

</style>
