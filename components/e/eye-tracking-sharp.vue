<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mg1fkibct"/><path class="wbakugb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-tracking-sharp" /></template>
<style>
.mg1fkibct {
  d: path("M2.75 10c1.65-3.5 4.6-5.75 8-5.75s6.35 2.25 8 5.75c-1.65 3.5-4.6 5.75-8 5.75S4.4 13.5 2.75 10Z");
}

.wbakugb1s {
  d: path("M8.25 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.46 3.45l6.08 2.6l.46.2l-.46.19l-2.08.87l-.46.19l-.18.47l-.89 2.31l-.18.47l-.17-.47l-2.41-6.56l-.17-.47z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
