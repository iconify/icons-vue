<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="si4a-zbah"/><path class="m36tppbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:denim-jacket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m36tppbdc {
  d: path("M9 3L7.5 7.5l4.5 2l4.5-2L15 3m-3 6.5v11m-4.5-9h.25a1.5 1.5 0 0 1 1.5 1.5v.25a1.5 1.5 0 0 1-1.5 1.5H7.5a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5m8.75 0h.25A1.5 1.5 0 0 1 18 13v.25a1.5 1.5 0 0 1-1.5 1.5h-.25a1.5 1.5 0 0 1-1.5-1.5V13a1.5 1.5 0 0 1 1.5-1.5");
}

.si4a-zbah {
  d: path("M9 3L4.5 4.5C3.5 4.83 3 5.75 3 6.75V20.5h18V6.75c0-1-.5-1.92-1.5-2.25L15 3");
}

</style>
