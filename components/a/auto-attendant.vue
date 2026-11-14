<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjw8yqb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-attendant" /></template>
<style>
.fjw8yqb3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 6v3l-4 1.5l-1.5-2c-2.25 1-4.5 3.25-5.5 5.5l2 1.5l-1.5 4H6.5a2 2 0 0 1-2-2C5 10.25 10.75 4.5 18 4a2 2 0 0 1 2.5 2ZM15 15h.01M18 15h.01M21 15h.01M15 18h.01M18 18h.01M21 18h.01M15 21h.01M18 21h.01M21 21h.01");
}

</style>
