<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8cem1bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-up-right-dashed-panel-fill" /></template>
<style>
.n8cem1bzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11.5H11.9989C12.2751 11.5 12.5 11.7239 12.5 12V21M3 21L12 12M10.5 3H13.5M21 10.5V13.5M3 7V6C3 4.34315 4.34315 3 6 3M18 3C19.6569 3 21 4.34315 21 6M17 21H18C19.6569 21 21 19.6569 21 18");
}

</style>
