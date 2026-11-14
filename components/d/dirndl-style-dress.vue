<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt0fztbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dirndl-style-dress" /></template>
<style>
.zt0fztbtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h2q2 2 4 0h2l-1 7.5c3 1.5 5.5 5.5 6 10H3c.5-4.5 3-8.5 6-10Zm1 7.5h6l-3 7.25Z");
}

</style>
