<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r6uvgekkq"/><path class="c6jrm--lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:adr" /></template>
<style>
.c6jrm--lm {
  d: path("M16.25 10.25C16 9.5 15.4 9 14.5 9c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1m1.75-6.25V9m0 6v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r6uvgekkq {
  d: path("m3.774 10.378l3.438-4.375A2.63 2.63 0 0 1 9.276 5h9.099A2.625 2.625 0 0 1 21 7.625v8.75A2.625 2.625 0 0 1 18.375 19H9.276a2.63 2.63 0 0 1-2.064-1.003l-3.438-4.375a2.625 2.625 0 0 1 0-3.244M7.5 12h.01");
}

</style>
