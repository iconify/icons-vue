<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q0rjtkgun"/><path class="l0klitb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backpack-sharp" /></template>
<style>
.l0klitb6q {
  d: path("M8 13.5h8v5H8z");
}

.q0rjtkgun {
  d: path("M4.75 6.25h14.5v15H4.75zm4.75 0v-1a2.5 2.5 0 0 1 5 0v1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
