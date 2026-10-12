<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l2c-5vyrk"/><path class="po156s2av"/><path class="l9t5c0bdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ev-plug-sharp" /></template>
<style>
.l2c-5vyrk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5h11a7.25 7.25 0 1 1-11 0Z");
}

.l9t5c0bdm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.5v4.75h9.25");
}

.po156s2av {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 7.75h.01m2.99-.5h.01m2.99.5h.01m-4.76 3.5h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
