<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ntj-oyb8g"/><path class="p8a7rmkzk"/><path class="az1hpy9gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lab-coat-outline-regular" /></template>
<style>
.az1hpy9gr {
  d: path("M12 9v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ntj-oyb8g {
  d: path("M6 21V7l3 -3h6l3 3v14Z");
}

.p8a7rmkzk {
  d: path("m7 4 5 5 5 -5");
}

</style>
