<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ihm63ijnz"/><path class="d0jfembef"/><path class="rwn8pbbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:datetime-picker" /></template>
<style>
.d0jfembef {
  d: path("M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ihm63ijnz {
  d: path("M12.5 20.5h-9V5h17v7.5M8 3v4m8-4v4M3.5 10h17M8 3v4m8-4v4M3.5 10h17");
}

.rwn8pbbrv {
  d: path("M18 16.5V18h1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
