<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="dcnzi9b5t"/><path class="kk0m3_b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:information-sign-sharp" /></template>
<style>
.dcnzi9b5t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.25h.01");
}

.kk0m3_b7x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 10.5H12V17m-1.75 0h3.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywno-sh7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
