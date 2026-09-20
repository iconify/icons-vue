<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o47um4vmm"/><path class="j5baogbem"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crayon-outline-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.j5baogbem {
  d: path("M8 11h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o47um4vmm {
  d: path("M8 21V9l4 -4 4 4v12Z");
}

</style>
