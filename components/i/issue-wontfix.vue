<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gdjknqbvl"/><path class="n0-lk6d5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:issue-wontfix" /></template>
<style>
.gdjknqbvl {
  d: path("M10.5 19a8.5 8.5 0 1 1 8.5-8.5");
}

.n0-lk6d5k {
  d: path("M8 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm7.5 5l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
