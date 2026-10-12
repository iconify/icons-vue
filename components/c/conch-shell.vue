<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1afgcbfn"/><path class="bujs9s81r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conch-shell" /></template>
<style>
.bujs9s81r {
  d: path("M15.5 10.5c1.75 1.25 2.5 3.5 2 5.75M6.25 9c1.25-.25 2.5 0 3.5.75m-2 1.75q3-.75 5.25 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1afgcbfn {
  d: path("m4.93 4.2l.64.1q1.18.2 1.43.83q.25.62 1.45.51l.35-.03q1.2-.11 1.58.64q.37.75 1.56.61l1.87-.22q1.19-.14 2.16.57l2.81 2.08q.97.71 1.21 1.89l.52 2.64q.24 1.18 0 2.35l-.77 3.66q-.24 1.17-1.31.63l-2.36-1.17q-1.07-.54-2.27-.59l-3.1-.15q-1.2-.05-2.02-.92l-2.61-2.76q-.82-.87-.93-2.07l-.28-3.1q-.11-1.2-.37-2.37l-.48-2.16Q3.75 4 4.93 4.2");
}

</style>
