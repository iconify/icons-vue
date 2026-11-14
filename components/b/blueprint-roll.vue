<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cbi4hr7gq"/><path class="h69bgqbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blueprint-roll" /></template>
<style>
.cbi4hr7gq {
  d: path("M3.5 3.5h17a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

.h69bgqbut {
  d: path("M12.5 9.5v11h9v-14M7 3.5v6m8.5 4.5h3m-3 3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
