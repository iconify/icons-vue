<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfm_g65hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backyard" /></template>
<style>
.cfm_g65hg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5a8.5 6 0 0 1 17 0Zm0 0h17a8.5 6.5 0 0 1-17 0M7 14.75L5.5 21.5M17 14.75l1.5 6.75M12 16v5.5m-1.5-15h3");
}

</style>
