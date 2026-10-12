<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="plrtpqbug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:footer-bar-sharp" /></template>
<style>
.plrtpqbug {
  d: path("M2.75 15h18.5v5.25H2.75v-2.5Z");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
