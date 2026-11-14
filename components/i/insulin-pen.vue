<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzdfk95-p"/><path class="tl-fusx-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insulin-pen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tl-fusx-p {
  d: path("M16.066 5.813za1.25 1.25 0 0 1 1.768 0l.353.353a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0l-.353-.353a1.25 1.25 0 0 1 0-1.768m-5.48 3.359l2.475-2.475m-2.475 2.475l.884.883");
}

.xzdfk95-p {
  d: path("m6.697 14.828l7.071-7.071a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475l-7.071 7.071a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475m0 2.475l-1.415 1.415");
}

</style>
