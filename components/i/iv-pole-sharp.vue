<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zcd123h1a"/><path class="qaiu7ub3f"/><path class="fmv9i8byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iv-pole-sharp" /></template>
<style>
.fmv9i8byg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h4.5v6.25H5z");
}

.qaiu7ub3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 20.5h.01m6.49 0h.01m6.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zcd123h1a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 5.75v-3h9.5v3m-4.75-3V18.5m0 0l-6.5.75m6.5-.75l6.5.75M12 18.5v.75");
}

</style>
