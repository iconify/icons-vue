<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pwab0wbqh"/><path class="sr9zhccfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chevrons-left-sharp" /></template>
<style>
.pwab0wbqh {
  d: path("M18.5 5.25L11.75 12l6.75 6.75");
}

.sr9zhccfd {
  d: path("M12.25 5.25L5.5 12l6.75 6.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
