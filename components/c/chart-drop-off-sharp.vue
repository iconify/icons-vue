<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c9csrccrc"/><path class="jqn8oswyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-drop-off-sharp" /></template>
<style>
.c9csrccrc {
  d: path("M3.75 10.25h3.5v10h-3.5zm6.5 3h3.5v7h-3.5zm6.5 3h3.5v4h-3.5zM5.25 2.75l6.5 6.5l3-3l5.5 5.5");
}

.jqn8oswyg {
  d: path("M20.25 7.25v4.5h-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
