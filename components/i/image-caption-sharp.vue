<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="crhi1p5gr"/><path class="gwucx7bfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-caption-sharp" /></template>
<style>
.crhi1p5gr {
  d: path("M2.75 2.75h18.5v12.5H2.75z");
}

.gwucx7bfe {
  d: path("m5.75 12.25l3.5-3.75l2.5 2.5l2-2l3.5 3.25M5.75 18.5h12.5M8.5 21.25h7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
