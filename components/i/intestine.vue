<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pd9r2sv9q"/><path class="nki7o-44j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:intestine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nki7o-44j {
  d: path("M9.25 9.25h4.5a1.5 1.5 0 0 1 0 3h-3.5a1.5 1.5 0 0 0 0 3h3.5a1.5 1.5 0 0 1 0 3h-4.5");
}

.pd9r2sv9q {
  d: path("M2.75 19.75V6.5A3.5 3.5 0 0 1 6.25 3h11.5a3.5 3.5 0 0 1 3.5 3.5v13.25a1.5 1.5 0 0 1-3 0V7.5a1.5 1.5 0 0 0-1.5-1.5h-9.5a1.5 1.5 0 0 0-1.5 1.5v12.25a1.5 1.5 0 0 1-3 0");
}

</style>
