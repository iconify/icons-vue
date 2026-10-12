<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q18bogbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jalebi" /></template>
<style>
.q18bogbmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.25a1.25 1.25 0 0 1 2.5 0a2.5 2.5 0 0 1-5 0a3.75 3.75 0 0 1 7.5 0a5 5 0 0 1-10 0a6.25 6.25 0 0 1 12.5 0a7.5 7.5 0 0 1-15 0M3.25 21h17.5");
}

</style>
