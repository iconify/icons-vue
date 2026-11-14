<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtl99p2rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fedora" /></template>
<style>
.jtl99p2rd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 14l1-6.5c.3-1.5 1.5-2 4-1c2.5-1 3.7-.5 4 1l1 6.5Zm-4.5 1.25C4 14 6 14 7 14h10c1 0 3 0 4.5 1.25c-2.5 1.5-16.5 1.5-19 0m4.75-3h9.5M12 6.5v2.75");
}

</style>
