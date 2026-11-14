<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj-8llbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bone-tag" /></template>
<style>
.sj-8llbed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.75h10a2.25 2.25 0 1 1 2.5 1.75a2.25 2.25 0 1 1-2.5 1.75H7a2.25 2.25 0 1 1-2.5-1.75A2.25 2.25 0 1 1 7 13.75M9.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 9.5v4.25");
}

</style>
