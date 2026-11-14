<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgbkgy7xs"/><path class="e6-hp13xz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gene-therapy" /></template>
<style>
.e6-hp13xz {
  d: path("M13 2.5c0 4-7 5-7 9.5c0 3.451 4.117 4.844 6.037 7.11M7.75 4h3.5m-3.5 8h3.5m-3.5 8h3.5m8.695-4.945za1.25 1.25 0 0 1 0 1.768l-2.122 2.122a1.25 1.25 0 0 1-1.768 0a1.25 1.25 0 0 1 0-1.768l2.122-2.122a1.25 1.25 0 0 1 1.768 0m-3.89 3.89l-1.591 1.591m4.243-6.718l2.475 2.475");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgbkgy7xs {
  d: path("M6 2.5c0 4 7 5 7 9.5s-7 5.5-7 9.5");
}

</style>
