<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ci7h_2bxp"/><path class="gbrucpbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-label" /></template>
<style>
.ci7h_2bxp {
  d: path("M8 5h11a2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19H8l-5.5-7Z");
}

.gbrucpbwa {
  d: path("M13.5 8q.5 3.5 4 4q-3.5.5-4 4q-.5-3.5-4-4q3.5-.5 4-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
