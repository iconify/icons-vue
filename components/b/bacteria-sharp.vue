<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s_lmc1beg"/><path class="lrurejw1i"/><path class="geoi7qkvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bacteria-sharp" /></template>
<style>
.geoi7qkvq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 8c.25-1.75 1.75-2 2-3.75M18 9.75c1.75-.25 2-1.75 3.25-2");
}

.lrurejw1i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15.5h.01M12 12.25h.01");
}

.s_lmc1beg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.04 13.92l5.74-4.82l2.49-2.09l2.09 2.49l2.09 2.49l-2.49 2.09l-5.74 4.82l-2.49 2.09l-2.09-2.49l-2.09-2.49z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
