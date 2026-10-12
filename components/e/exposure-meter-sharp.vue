<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e0il_7__t"/><path class="cs185qb-c"/><path class="f25x8hzed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:exposure-meter-sharp" /></template>
<style>
.cs185qb-c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01");
}

.e0il_7__t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5a8.5 8.5 0 0 1 17 0ZM12 14l2.25-3.25");
}

.f25x8hzed {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20h14");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
