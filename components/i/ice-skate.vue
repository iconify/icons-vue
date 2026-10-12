<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojgn3bcdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-skate" /></template>
<style>
.ojgn3bcdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.25a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v5.5l4.5 1.75a4 4 0 0 1 2.5 3.7v1.55a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1ZM8 6.75h2m-2 3h2m-2.25 7v3.5m8.25-3.5v3.5m-12.25 0h14.5a2.5 2.5 0 0 0 2.5-2.5");
}

</style>
