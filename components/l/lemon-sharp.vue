<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w7exbdcbq"/><path class="n_cv__85c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lemon-sharp" /></template>
<style>
.n_cv__85c {
  d: path("M18.5 5.5C18.25 4 19 3 21 2.75c.25 1.75-.75 2.75-2.5 2.75ZM8 15c-.75-2.5 1-5.75 3.5-7");
}

.w7exbdcbq {
  d: path("M5.5 18.5C4 17 4.5 15.5 4 14C2.5 9.5 9.5 2.5 14 4c1.5.5 3 0 4.5 1.5s1 3 1.5 4.5c1.5 4.5-5.5 11.5-10 10c-1.5-.5-3 0-4.5-1.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
