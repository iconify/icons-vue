<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-aeaorem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bookmark-check" /></template>
<style>
.l-aeaorem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25a2.5 2.5 0 0 1 2.5-2.5h7.5a2.5 2.5 0 0 1 2.5 2.5v14.6c0 .85-.95 1.3-1.6.85L12 17.25L7.35 20.7c-.65.45-1.6 0-1.6-.85Zm3.5 2h5.5");
}

</style>
