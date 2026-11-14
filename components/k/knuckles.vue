<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2dlhbcdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:knuckles" /></template>
<style>
.j2dlhbcdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7a2.25 2.25 0 0 1 4.5 0A2.25 2.25 0 0 1 12 7a2.25 2.25 0 0 1 4.5 0A2.25 2.25 0 0 1 21 7v8c0 3-2.5 5-5.5 5h-7c-3 0-5.5-2-5.5-5Zm4.5 0v3.5M12 7v3.5M16.5 7v3.5M3 14h9.5");
}

</style>
