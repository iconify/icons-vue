<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn2kavb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:agent-team" /></template>
<style>
.sn2kavb-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6 21c0-4.25 2.75-7 6-7s6 2.75 6 7M2.5 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm15.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-15.5 10c0-3.5.75-5.25 2.5-5.25m16.5 5.25c0-3.5-.75-5.25-2.5-5.25");
}

</style>
