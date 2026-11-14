<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8hqze9vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chocolate-bar" /></template>
<style>
.x8hqze9vl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 3.5h8.75A2.625 2.625 0 0 1 19 6.125v11.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 17.875V6.125A2.625 2.625 0 0 1 7.625 3.5M5 9.25h14m-14 5.5h14M12 3.5v17");
}

</style>
