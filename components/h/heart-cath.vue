<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sczsh_p9r"/><path class="f4dchtb7j"/><path class="so9r8pb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-cath" /></template>
<style>
.f4dchtb7j {
  d: path("M2.5 21.5c2.5-1.5 5-3.5 7-6c1.5-2 2.75-4 3.5-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sczsh_p9r {
  d: path("M13.75 16.75s-7-4.25-7-8.75c0-2 1.5-3.75 3.75-3.75c1.25 0 2.5.75 3.25 2c.75-1.25 2-2 3.25-2c2.25 0 3.75 1.75 3.75 3.75c0 4.5-7 8.75-7 8.75");
}

.so9r8pb1c {
  fill: currentColor;
  d: path("M12.25 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
