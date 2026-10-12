<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="fef3bqehl"/><path class="qu0bxjbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:authenticator-app-sharp" /></template>
<style>
.fef3bqehl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.92 5.88l2.41.99l.92.38v3.06l-.73.68l-2.79 2.58l-.73.68l-.73-.68l-2.79-2.58l-.73-.68V7.25l.92-.38l2.41-.99l.92-.38z");
}

.qu0bxjbhg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17.25h.01m3.99 0h.01m3.99 0h.01");
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
