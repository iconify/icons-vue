<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="fp13a0boh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-romance" /></template>
<style>
.fp13a0boh {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M12.75 13s-4-2.25-4-5c0-1.25 1-2.25 2.25-2.25c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2.25 1 2.25 2.25c0 2.75-4 5-4 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

</style>
