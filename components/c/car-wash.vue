<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhlj1fbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-wash" /></template>
<style>
.jhlj1fbpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 15.25l1.65-4.5A1.75 1.75 0 0 1 7.05 9.5h9.9a1.75 1.75 0 0 1 1.65 1.25l1.65 4.5v5a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm.5-1h15.5M6.5 17.75H8m8 0h1.5M7 2.75c.75 1 1.5 1.85 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.9.75-1.75 1.5-2.75m5 0c.75 1 1.5 1.85 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.9.75-1.75 1.5-2.75m5 0c.75 1 1.5 1.85 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.9.75-1.75 1.5-2.75");
}

</style>
