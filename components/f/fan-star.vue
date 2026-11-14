<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akvv67b3y"/><path class="dl8615bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fan-star" /></template>
<style>
.akvv67b3y {
  d: path("M12 4a3.25 3.25 0 0 1 5.75 2.25A3.25 3.25 0 0 1 20 12a3.25 3.25 0 0 1-2.25 5.75A3.25 3.25 0 0 1 12 20a3.25 3.25 0 0 1-5.75-2.25A3.25 3.25 0 0 1 4 12a3.25 3.25 0 0 1 2.25-5.75A3.25 3.25 0 0 1 12 4");
}

.dl8615bii {
  d: path("m12.625 8.875l.283.735a1.5 1.5 0 0 0 1.293.958l.853.061a.621.621 0 0 1 .321 1.121l-.527.383a1.5 1.5 0 0 0-.56 1.625l.217.759a.663.663 0 0 1-1.005.733l-.668-.445a1.5 1.5 0 0 0-1.664 0l-.668.445a.663.663 0 0 1-1.005-.733l.217-.759a1.5 1.5 0 0 0-.56-1.625l-.527-.383a.621.621 0 0 1 .321-1.121l.853-.061a1.5 1.5 0 0 0 1.293-.958l.283-.735a.67.67 0 0 1 1.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
