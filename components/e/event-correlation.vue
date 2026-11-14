<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7nphcbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-correlation" /></template>
<style>
.m7nphcbed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 13a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m.75-8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-7 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 9.75V7m-2.5 8L7 17m7.5-2l2.5 2");
}

</style>
