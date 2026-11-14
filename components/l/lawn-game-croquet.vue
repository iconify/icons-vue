<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohri6tbao"/><path class="rcoo5yp1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-game-croquet" /></template>
<style>
.ohri6tbao {
  d: path("M2.5 14.5h4v6h-4Zm2 0L7 3m2.25 17.5V12a4.75 4.75 0 0 1 9.5 0v8.5");
}

.rcoo5yp1h {
  d: path("M12 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
