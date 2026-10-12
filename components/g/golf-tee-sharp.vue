<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="l0r7vlbov"/><path class="v7uj6_b2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:golf-tee-sharp" /></template>
<style>
.l0r7vlbov {
  cx: 12px;
  cy: 7.25px;
  r: 4.5px;
}

.v7uj6_b2g {
  d: path("M7.35 14.75h9.9l-.47.37l-2.81 2.26l-.47.37v2l-.42.42l-.66.66l-.42.42l-.42-.42l-.66-.66l-.42-.42v-2l-.47-.37l-2.81-2.26l-.47-.37z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
