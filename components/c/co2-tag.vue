<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="joem8zb5c"/><path class="zkv086b3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:co2-tag" /></template>
<style>
.joem8zb5c {
  d: path("M8.5 5h11a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-11l-6-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zkv086b3n {
  d: path("M5.25 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7 3.25a1.75 1.75 0 0 1 0-3.5a2.75 2.75 0 0 1 4.5 0a1.75 1.75 0 0 1 0 3.5Z");
}

</style>
