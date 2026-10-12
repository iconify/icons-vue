<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf_31rbpy"/><path class="h4kmvibqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-annotation-sharp" /></template>
<style>
.h4kmvibqu {
  d: path("m7 17.25l3.75-4L14 15.5l6.25-5.25m-9.75-7.5h9.75V8h-4.5l-.65.76l-.2.23l-.65.76l-.65-.76l-.2-.23l-.65-.76H9.5V2.75zm1.75 2.75h5.25");
}

.vf_31rbpy {
  d: path("M3.75 3.75v16.5h16.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
