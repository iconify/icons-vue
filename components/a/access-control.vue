<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="reo2tm3sp"/><path class="j_qsqhbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-control" /></template>
<style>
.j_qsqhbdd {
  d: path("M6 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5-1h5m-5 3.5h3m-.75 6l2 2L21 15.75");
}

.reo2tm3sp {
  d: path("M11.3 17.5H2.5v-14h19v8.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
