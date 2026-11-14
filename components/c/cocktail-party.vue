<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld2r2vc3u"/><path class="l5wez7y9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cocktail-party" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5wez7y9l {
  d: path("M11.25 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.ld2r2vc3u {
  d: path("M7.621 4.5h8.758a1.5 1.5 0 0 1 1.06 2.561l-4.378 4.378a1.5 1.5 0 0 1-2.122 0L6.561 7.061A1.5 1.5 0 0 1 7.621 4.5m4.379 8v8m-4 0h8M17.5 2l-4.25 4.75");
}

</style>
