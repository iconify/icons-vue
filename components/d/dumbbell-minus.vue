<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvwxwhmqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dumbbell-minus" /></template>
<style>
.gvwxwhmqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5H8v12H4.5ZM16 15.2V4.5h3.5v10.7m-17-4.7h2m3.5 0h8m3.5 0h2M15 18h6");
}

</style>
