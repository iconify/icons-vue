<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uyn4oobxg"/><path class="b-rg60jdd"/><path class="eb8ny4zms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:academic-calendar" /></template>
<style>
.b-rg60jdd {
  d: path("m6.5 13.5l5.5-2l5.5 2l-5.5 2Z");
}

.eb8ny4zms {
  d: path("M9.25 14.5v2c0 1.75 5.5 1.75 5.5 0v-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uyn4oobxg {
  d: path("M3 4.5h18v17H3Zm0 4.25h18M8 2.5v4m8-4v4");
}

</style>
