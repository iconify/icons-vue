<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cfu2mbbua"/><circle class="z6httfbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:federated-learning-sharp" /></template>
<style>
.cfu2mbbua {
  d: path("M2.75 2.75h5v5h-5zm13.5 0h5v5h-5zM9.5 16.25h5v5h-5zm-1.75-8.5l1.8 1.27m6.7-1.27l-1.8 1.27M12 13.75v2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6httfbqu {
  cx: 12px;
  cy: 10.75px;
  r: 3px;
}

</style>
