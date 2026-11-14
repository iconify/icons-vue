<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psusbkerw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fishing-float" /></template>
<style>
.psusbkerw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M12 12v9.5M2.5 15q2.375-1.5 4.75 0T12 15t4.75 0t4.75 0m-14-7.5h9");
}

</style>
