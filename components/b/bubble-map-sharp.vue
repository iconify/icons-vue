<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="obys3nk4x"/><circle class="bex1-ibcs"/><circle class="sgu7b2w-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bubble-map-sharp" /></template>
<style>
.bex1-ibcs {
  cx: 9.25px;
  cy: 10.5px;
  r: 2.75px;
}

.obys3nk4x {
  d: path("m3.69 5.4l4.12-1.55l.94-.35l.94.33l4.62 1.59l.94.33l.94-.35l4.12-1.55l.94-.35v14.75l-.94.35l-4.12 1.55l-.94.35l-.94-.33l-4.62-1.59l-.94-.33l-.94.35l-4.12 1.55l-.94.35V5.75z");
}

.sgu7b2w-a {
  cx: 15.5px;
  cy: 14.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
