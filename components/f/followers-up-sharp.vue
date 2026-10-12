<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="msx4mwb6m"/><path class="o-48nmbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:followers-up-sharp" /></template>
<style>
.msx4mwb6m {
  cx: 8px;
  cy: 7px;
  r: 3.25px;
}

.o-48nmbmt {
  d: path("M2.75 19.5a5.25 5.25 0 0 1 10.5 0v.75H2.75zm13 .75v-3m2.75 3v-6.5m2.75 6.5v-10");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
