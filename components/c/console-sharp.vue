<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="buurvcm9m"/><path class="rbx908bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:console-sharp" /></template>
<style>
.buurvcm9m {
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 4h18.5");
}

.rbx908bye {
  d: path("m6.5 11l1.75 1.5L6.5 14m4.25-1.5h6.75m-11 4h11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
