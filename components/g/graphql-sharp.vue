<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yo8g9ybef"/><path class="e31p8lb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:graphql-sharp" /></template>
<style>
.e31p8lb9v {
  d: path("m12.38 7.4l3.79 6.58l.38.65h-9.1l.38-.65l3.8-6.58l.37-.65z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yo8g9ybef {
  d: path("m12.87 3l6.49 3.75l.87.5v9.5l-.87.5L12.87 21l-.87.5l-.87-.5l-6.49-3.75l-.87-.5v-9.5l.87-.5L11.13 3l.87-.5z");
}

</style>
