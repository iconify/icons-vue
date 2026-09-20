<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mp3b81b8y"/><path class="sur-qkf7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cave-outline-regular" /></template>
<style>
.mp3b81b8y {
  d: path("M3 21v-9l9 -9 9 9v9Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sur-qkf7m {
  d: path("M7 21a5 5 0 0 1 10 0");
}

</style>
