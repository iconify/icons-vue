<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rue9oxbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:abacus-fill" /></template>
<style>
.rue9oxbut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3V21M19 3V21M3 21H21M5 8H19M5 15H19M9 6.5V9.5M13 6.5V9.5M11 13.5V16.5M15 13.5V16.5");
}

</style>
