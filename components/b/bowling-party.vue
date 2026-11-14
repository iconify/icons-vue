<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixylfwgdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bowling-party" /></template>
<style>
.ixylfwgdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16A5.25 5.25 0 1 0 13 16a5.25 5.25 0 1 0-10.5 0m14 5.5c-.75-4-.75-7.25.75-10.25c.5-1-.5-2.75-.5-5s.75-3.75 2-3.75s2 1.5 2 3.75s-1 4-.5 5c1.5 3 1.5 6.25.75 10.25ZM6 14.5h.01m2.49-1.25h.01M9.25 16h.01");
}

</style>
