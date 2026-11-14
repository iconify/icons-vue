<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yudiqacsm"/><path class="nj7mcwn_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:induction-hob" /></template>
<style>
.nj7mcwn_a {
  d: path("M5.5 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm5.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm6-2.5l2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yudiqacsm {
  d: path("M2.5 3h19v18h-19Z");
}

</style>
