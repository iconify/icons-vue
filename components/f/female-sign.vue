<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0n4pbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:female-sign" /></template>
<style>
.kr0n4pbye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a5.5 5.5 0 1 1 0 11a5.5 5.5 0 1 1 0-11m0 11v7M8.75 18h6.5");
}

</style>
