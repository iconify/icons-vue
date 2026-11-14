<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6ebysbxr"/><path class="oqn8y9gdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cargo-seal-number" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqn8y9gdq {
  d: path("M12 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 0c-6 0-8.5 2.5-8.5 6.5v6m7-8h6m-6 3H14m-3.5 3h5");
}

.s6ebysbxr {
  d: path("M11 3.5h5A3.5 3.5 0 0 1 19.5 7v11a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 7.5 18V7A3.5 3.5 0 0 1 11 3.5");
}

</style>
