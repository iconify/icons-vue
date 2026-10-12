<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b-4y7acsg"/><path class="pigikqbbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battery-charging-sharp" /></template>
<style>
.b-4y7acsg {
  d: path("M2.75 6.75h16v10.5h-16zm18.5 3.75v3");
}

.pigikqbbw {
  d: path("m11.75 9l-2.5 3.25h4.5l-2.5 3.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
