<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlqlzmbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-fantasy-film" /></template>
<style>
.xlqlzmbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.625 4.75l.272.652a1.5 1.5 0 0 0 1.269.918l.709.055a.698.698 0 0 1 .414 1.215l-.618.556a1.5 1.5 0 0 0-.452 1.479l.156.625a.617.617 0 0 1-.929.67l-.641-.408a1.5 1.5 0 0 0-1.61 0l-.641.408a.617.617 0 0 1-.929-.67l.156-.625a1.5 1.5 0 0 0-.452-1.479l-.618-.556a.698.698 0 0 1 .414-1.215l.709-.055a1.5 1.5 0 0 0 1.269-.918l.272-.652a.677.677 0 0 1 1.25 0M3.5 20.5l7-7");
}

</style>
