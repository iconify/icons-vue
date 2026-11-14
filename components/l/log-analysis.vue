<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eyh9o1-sy"/><path class="p9k80vbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:log-analysis" /></template>
<style>
.eyh9o1-sy {
  d: path("M14 21.5H4.5v-19h15v10.1M8.5 7h.01m2.74 0h4.25m-7 4h.01m2.74 0h4.25m-7 4h.01m2.74 0h1.6");
}

.p9k80vbmd {
  d: path("M15 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.25 1.75L21 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
