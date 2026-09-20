<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zddikdsez"/><path class="emo-jf0pj"/><path class="teggaxbsd"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:birdwatching-outline-regular" /></template>
<style>
.emo-jf0pj {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.teggaxbsd {
  d: path("M8 16v4");
}

.zddikdsez {
  d: path("M8 16c-3 0 -5 -3 -5 -6s2 -5 5 -5 5 2 5 5l4 -4v8c-2 -1 -3 -2 -4 -3 -1 3 -3 5 -5 5");
}

</style>
