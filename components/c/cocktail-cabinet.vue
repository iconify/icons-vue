<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-fxntbcu"/><path class="naca-ibqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cocktail-cabinet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-fxntbcu {
  d: path("M8.25 4.5h7.5a1.75 1.75 0 0 1 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75V6.25A1.75 1.75 0 0 1 8.25 4.5m-3.5 1l-.994.568A1.5 1.5 0 0 0 3 7.37v9.26a1.5 1.5 0 0 0 .756 1.302l.994.568a1.17 1.17 0 0 0 1.75-1.016V6.516A1.17 1.17 0 0 0 4.75 5.5m14.5 0l.994.568A1.5 1.5 0 0 1 21 7.37v9.26a1.5 1.5 0 0 1-.756 1.302l-.994.568a1.17 1.17 0 0 1-1.75-1.016V6.516A1.17 1.17 0 0 1 19.25 5.5m-12.75 9h11");
}

.naca-ibqe {
  d: path("M9.5 8h5L12 11Zm2.5 3v3.5");
}

</style>
