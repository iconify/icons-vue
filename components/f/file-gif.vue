<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gqhlvlk8q"/><path class="dmxdi42id"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-gif" /></template>
<style>
.dmxdi42id {
  d: path("M15 2.5v4a2 2 0 0 0 2 2h4m-10.75 4h-2.5a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h2.5v-2.75H8.5M13 12.5v6m5.25-6h-2.5v6m0-3h2");
}

.gqhlvlk8q {
  d: path("M5.5 2.5H15l6 6V19a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 19V5a2.5 2.5 0 0 1 2.5-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
