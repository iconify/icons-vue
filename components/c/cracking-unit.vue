<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3mmsobwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cracking-unit" /></template>
<style>
.n3mmsobwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21V6a2.5 2.5 0 0 1 5 0v15M4 21h16M9.5 9H4m0-1.5v3m10.5 4H20m0-1.5v3");
}

</style>
