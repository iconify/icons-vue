<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="guvuh5bhl"/><circle class="r9-7jjbjg"/><path class="r6bu50dmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:growth-chart-sharp" /></template>
<style>
.guvuh5bhl {
  d: path("M4 2.75h6v18.5H4zM4 6.5h2.5M4 10h3.5M4 13.5h2.5M4 17h3.5M10 5h8.75");
}

.r6bu50dmx {
  d: path("M12.5 21.25v-4a3.25 3.25 0 0 1 6.5 0v4Z");
}

.r9-7jjbjg {
  cx: 15.75px;
  cy: 9.5px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
