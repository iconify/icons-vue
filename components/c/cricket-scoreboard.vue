<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gegaziaej"/><path class="fj_875bzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricket-scoreboard" /></template>
<style>
.fj_875bzk {
  d: path("M15 7h3v6h-3Z");
}

.gegaziaej {
  d: path("M2.5 3.5h19v13h-19Zm4.5 13V21m10-4.5V21M8 7v6m2.75 0l1.5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
