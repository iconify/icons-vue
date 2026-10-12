<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k_tw80b1o"/><path class="kwl8nky0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:greenhouse-farm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_tw80b1o {
  d: path("M2.75 21.25V12a9.25 9.25 0 0 1 18.5 0v9.25ZM7 4.25v17m10-17v17");
}

.kwl8nky0k {
  d: path("M10 21.25v-4.5a2 2 0 0 1 4 0v4.5");
}

</style>
