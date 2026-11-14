<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jesvjub2n"/><path class="tths0dbed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hangman" /></template>
<style>
.jesvjub2n {
  d: path("M4.5 21.5h10m-6.5 0v-18h8.5V6");
}

.tths0dbed {
  d: path("M14 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 2.5v5m-3-3h6m-3 3L14 19.5m2.5-3.5l2.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
