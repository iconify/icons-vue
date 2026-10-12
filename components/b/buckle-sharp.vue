<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gsyup9wpv"/><path class="y-0wh5ukk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buckle-sharp" /></template>
<style>
.gsyup9wpv {
  d: path("M3.25 5.25h17.5v13.5H3.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-0wh5ukk {
  d: path("M7.75 8.75h9.5v6.5H6.75v-6.5zm-3 3.25H14");
}

</style>
