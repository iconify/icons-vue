<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="o9zalemks"/><path class="xvg8y8b2c"/><path class="a_l4tsbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-face-sharp" /></template>
<style>
.a_l4tsbuy {
  d: path("m8.5 12.75l1.375 1.375l1.375-1.375m1.5 0l1.375 1.375L15.5 12.75m-4.75 4l1.25.833l1.25-.833");
}

.o9zalemks {
  cx: 12px;
  cy: 13.5px;
  r: 6px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xvg8y8b2c {
  d: path("M4.25 17.5a8.75 8.75 0 1 1 15.5 0");
}

</style>
