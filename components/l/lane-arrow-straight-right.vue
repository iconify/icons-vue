<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dia4z7d4z"/><path class="s0216tidb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-arrow-straight-right" /></template>
<style>
.dia4z7d4z {
  d: path("M9 21.5V3M4 8l5-5l5 5M9 20a5 5 0 0 1 5-5h6");
}

.s0216tidb {
  d: path("M16.5 11.5L20 15l-3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
