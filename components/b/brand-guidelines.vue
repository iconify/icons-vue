<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e_krceh5v"/><path class="og8zfpcca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brand-guidelines" /></template>
<style>
.e_krceh5v {
  d: path("M12 5.5Q9 3.25 3 4v14.5q6-.75 9 1.5Zm0 0q3-2.25 9-1.5v14.5q-6-.75-9 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og8zfpcca {
  d: path("M7.5 8zA1.5 1.5 0 0 1 9 9.5A1.5 1.5 0 0 1 7.5 11A1.5 1.5 0 0 1 6 9.5A1.5 1.5 0 0 1 7.5 8M15 9h3m-3 4h3");
}

</style>
