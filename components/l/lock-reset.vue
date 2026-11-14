<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rbtgdp99g"/><path class="o4x-zoiyb"/><path class="upewqvbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lock-reset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o4x-zoiyb {
  d: path("M12 4.5a8.5 8.5 0 1 1-7.361 4.25");
}

.rbtgdp99g {
  d: path("M10.688 12h2.625a2.19 2.19 0 0 1 2.187 2.188v1.125a2.19 2.19 0 0 1-2.187 2.187h-2.625A2.19 2.19 0 0 1 8.5 15.313v-1.125A2.19 2.19 0 0 1 10.688 12M10 12v-1.25a2 2 0 0 1 4 0V12");
}

.upewqvbrp {
  d: path("m15 2l-3 2.5L15 7m-3 7.75h.01");
}

</style>
