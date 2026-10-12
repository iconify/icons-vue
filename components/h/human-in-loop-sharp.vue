<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s86wwrbuj"/><circle class="kz9qc0sgp"/><path class="ktn74f7hb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:human-in-loop-sharp" /></template>
<style>
.ktn74f7hb {
  d: path("M7.5 20.25c0-3 2-5.25 4.5-5.25s4.5 2.25 4.5 5.25v1h-9z");
}

.kz9qc0sgp {
  cx: 12px;
  cy: 9.75px;
  r: 2.25px;
}

.s86wwrbuj {
  d: path("M6.15 13.13a6.75 6.75 0 1 1 11.7 0m2.41-.65l-2.41.65l-.65-2.42");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
