<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-6v8o44a"/><path class="j9mpubb9t"/><path class="oqj-o0b2r"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:humidity-low-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9mpubb9t {
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.p-6v8o44a {
  fill: currentColor;
  d: path("m12 6 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
