<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c2s4_gvnh"/><path class="cc0-fv0tt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basilica-dome" /></template>
<style>
.c2s4_gvnh {
  d: path("M2.5 21V11H6v3h12v-3h3.5v10Z");
}

.cc0-fv0tt {
  d: path("M6 14a6 6 0 0 1 12 0m-6-6V2.5m-2 2h4M10.25 21v-2.25a1.75 1.75 0 0 1 3.5 0V21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
