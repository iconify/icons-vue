<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pp6gxjbpg"/><path class="q2w3p_b6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-fetch" /></template>
<style>
.pp6gxjbpg {
  d: path("M2.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm9.5 2a12.5 12.5 0 0 1 2.25 1.25m2.25 2A12.5 12.5 0 0 1 18 14m1 2.75a12.5 12.5 0 0 1 .5 3.25");
}

.q2w3p_b6o {
  d: path("M17.25 17.75L19.5 20l2.25-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
