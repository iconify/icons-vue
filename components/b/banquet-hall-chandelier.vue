<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uvnjnq4om"/><path class="h1dzrpbpy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banquet-hall-chandelier" /></template>
<style>
.h1dzrpbpy {
  d: path("M10.25 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM4 5c1.5 1.5 1.25 3.5 0 3.5S2.5 6.5 4 5Zm16 0c1.5 1.5 1.25 3.5 0 3.5s-1.5-2 0-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uvnjnq4om {
  d: path("M10 2.5h4m-2 0v15M2.5 11h3M4 11c0 6.5 16 6.5 16 0m-1.5 0h3");
}

</style>
