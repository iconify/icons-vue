<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz5ek8i3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:confetti-cannon" /></template>
<style>
.fz5ek8i3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.945 10.77l3.535 3.535l-7.425 7.425l-3.535-3.535ZM13 7l.75-3M16 10l3-.75M17.5 4.5h.01M20.5 13h.01M10 4h.01");
}

</style>
