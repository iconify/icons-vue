<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivirgum1t"/><path class="rzksocb9k"/><path class="y2edr1bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dashboard-share" /></template>
<style>
.ivirgum1t {
  d: path("M13.4 21.5H2.5v-19h19v8.8m-19-.3h19M11 11v6.6m0 .8v3.1");
}

.rzksocb9k {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5m2.25 9.75L15.75 18l4.5 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y2edr1bye {
  fill: currentColor;
  d: path("M19 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM14.5 18a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4.5 2.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
