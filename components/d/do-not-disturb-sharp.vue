<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="p1xamwbmi"/><path class="o6a500beq"/><path class="b7rz9-gsc"/><path class="j5rul6sow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:do-not-disturb-sharp" /></template>
<style>
.b7rz9-gsc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.05 10.36a4.25 4.25 0 1 0 3.57 7.66a1.15 1.15 0 0 0-.74-2.17a3.75 3.75 0 0 1-1.64-3.52a1.15 1.15 0 0 0-1.19-1.97Z");
}

.j5rul6sow {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.06 13.15h.01");
}

.o6a500beq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

.p1xamwbmi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5v18.5H5.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
