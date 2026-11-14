<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhqmqylrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:animal-welfare" /></template>
<style>
.xhqmqylrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.25C9.75 9 7.25 7 7.25 4.75c0-1.5 1-2.5 2.5-2.5q1.5 0 2.25 1.5q.75-1.5 2.25-1.5c1.5 0 2.5 1 2.5 2.5c0 2.25-2.5 4.25-4.75 5.5m9.5 1.25H19c-2 0-3.5 3.25-7 3.25c-3 0-5-2.25-6.75-4.5c-.75-.75-2.25 0-1.75 1c2 4.25 5 7.5 9 7.5h.843m2.657 1a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0m-.25-3h.01m2.74-1.5h.01m2.74 1.5h.01");
}

</style>
