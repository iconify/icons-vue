<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="akhyuacja"/><path class="kuy7wqbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gps-steering" /></template>
<style>
.akhyuacja {
  d: path("M3 13.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.kuy7wqbve {
  d: path("M8.5 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-5.5 0h5.5m4 0H18m-7.5 2V21M16 5a3 3 0 0 1 3 3m-3-6a6 6 0 0 1 6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
