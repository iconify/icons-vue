<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n-ivfjbhs"/><path class="c4jmp2bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artboard-poster" /></template>
<style>
.c4jmp2bxe {
  d: path("M9.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM9 17h6");
}

.n-ivfjbhs {
  d: path("M6 5.25h12v16H6ZM6 2.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
