<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaebbacbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bars-progress" /></template>
<style>
.vaebbacbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 8C21 8.5523 20.5523 9 20 9L4 9C3.4477 9 3 8.5523 3 8L3 4C3 3.4477 3.4477 3 4 3ZM4 15L20 15C20.5523 15 21 15.4477 21 16L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 16C3 15.4477 3.4477 15 4 15ZM15 3L15 9M10 15L10 21");
}

</style>
