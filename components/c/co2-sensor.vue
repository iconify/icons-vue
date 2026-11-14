<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n4vtn8gmu"/><path class="lze0lg4sk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:co2-sensor" /></template>
<style>
.lze0lg4sk {
  d: path("M6 8q2.25-2 4.5 0T15 8m-9 4.5q2.25-2 4.5 0t4.5 0m1 8.5h4a1.75 1.75 0 0 0 .25-3.5a3 3 0 0 0-5.75.5a1.5 1.5 0 0 0 1.5 3Z");
}

.n4vtn8gmu {
  d: path("M11.2 17.5H2.5v-15h16v10.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
