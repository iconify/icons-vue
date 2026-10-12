<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="lscd8kr5m"/><path class="ibg21sbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-rofl-sharp" /></template>
<style>
.ibg21sbpe {
  d: path("m11.56 10.66l2.078-2.417l.032 3.187m2.35.85l2.119-2.53l.001 3.3m-7.37.51l6.11 2.23a3.25 2.75 20 0 1-6.11-2.23ZM4.4 5.25l1.4 2.059V8A1.4 1.4 0 0 1 3 8v-.691z");
}

.lscd8kr5m {
  cx: 14.25px;
  cy: 13.5px;
  r: 7px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
