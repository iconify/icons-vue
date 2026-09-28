<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebf1etbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-2" /></template>
<style>
.ebf1etbfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2H14M4 7H20M6 7H18V19C18 20.6569 16.6569 22 15 22H9C7.34315 22 6 20.6569 6 19V7ZM10 11L10 18M14 11L14 18");
}

</style>
