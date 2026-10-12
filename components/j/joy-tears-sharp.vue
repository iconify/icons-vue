<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nr7ho51jq"/><path class="qygh0rbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joy-tears-sharp" /></template>
<style>
.nr7ho51jq {
  cx: 12px;
  cy: 10.5px;
  r: 7.75px;
}

.qygh0rbzt {
  d: path("M7.75 9L9 7.437L10.25 9m3.5 0L15 7.437L16.25 9m-8 3h7.5a3.75 3.75 0 0 1-7.5 0ZM4 17.25l1.25 1.641v.709a1.25 1.25 0 0 1-2.5 0v-.709zm16 0l1.25 1.641v.709a1.25 1.25 0 0 1-2.5 0v-.709z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
