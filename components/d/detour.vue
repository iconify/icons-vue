<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xikjqib6u"/><path class="xg0cf7bzy"/><path class="iefxfwiwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:detour" /></template>
<style>
.iefxfwiwf {
  fill: currentColor;
  d: path("M10.25 10h3.5v3.5h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xg0cf7bzy {
  d: path("m19.25 14l2.5 2.5l-2.5 2.5");
}

.xikjqib6u {
  d: path("M2.5 16.5h5v-9A2.5 2.5 0 0 1 10 5h4a2.5 2.5 0 0 1 2.5 2.5v9h5.25");
}

</style>
