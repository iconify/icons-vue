<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4tzxzl2o"/><path class="zusf7zbxz"/><path class="mwg8pgbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hose-timer" /></template>
<style>
.mwg8pgbcw {
  d: path("M11 10.5v2h1.75m-1.75 5v1a2.5 2.5 0 0 0 2.5 2.5h8");
}

.r4tzxzl2o {
  d: path("M2.5 4.5H11v3M6 2v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zusf7zbxz {
  d: path("M6 12.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
