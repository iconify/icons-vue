<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tw40btbsg"/><path class="s73rmnvbn"/><path class="y6cjf5j_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothes-tag" /></template>
<style>
.s73rmnvbn {
  d: path("M7.25 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.tw40btbsg {
  d: path("M5.636 12V5.636H12l9.546 9.546l-6.364 6.364Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6cjf5j_m {
  d: path("M7.75 7.75C5 5 3 5 2.5 2.5");
}

</style>
