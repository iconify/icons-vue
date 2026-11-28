<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cod0zxxhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hockey-puck" /></template>
<style>
.cod0zxxhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 9C22 11.2091 17.5228 13 12 13C6.4772 13 2 11.2091 2 9C2 6.7909 6.4772 5 12 5C17.5228 5 22 6.7909 22 9ZM2 9L2 15C2 17.2091 6.4772 19 12 19C17.5228 19 22 17.2091 22 15L22 9");
}

</style>
