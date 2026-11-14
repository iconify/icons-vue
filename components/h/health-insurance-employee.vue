<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jxluu6iob"/><path class="hai3wsu8z"/><path class="j125x-bxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-insurance-employee" /></template>
<style>
.hai3wsu8z {
  d: path("M3 2.5v7a9 7.5 0 0 0 18 0v-7");
}

.j125x-bxm {
  d: path("M12 17v.75a2 2 0 0 0 2 2h2.75m0 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.jxluu6iob {
  d: path("M6 3.75h12v8.5H6ZM9 8h.01M12 6.5h3m-3 3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
