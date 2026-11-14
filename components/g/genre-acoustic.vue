<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kemtgtbwv"/><path class="mc99srw0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:genre-acoustic" /></template>
<style>
.kemtgtbwv {
  d: path("M12 9.5c-2.75 0-4.5 1.25-4.5 3.25c0 1 .5 1.5.75 2c-1.75.75-2.75 2-2.75 3.5c0 2 2.5 3.25 6.5 3.25s6.5-1.25 6.5-3.25c0-1.5-1-2.75-2.75-3.5c.25-.5.75-1 .75-2c0-2-1.75-3.25-4.5-3.25Zm-1.75-7h3.5V6h-3.5ZM12 6v3.5");
}

.mc99srw0p {
  d: path("M10.25 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
