<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="a0rm1bb6b"/><path class="o40hxbbja"/><path class="myfbzx5xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hovercraft" /></template>
<style>
.a0rm1bb6b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5a2.75 2.75 0 0 1 5.5 0m-6.34 6.51l.43-2.52q.16-.99 1.16-.99h9.25q1 0 1.66.75l2.68 3q.66.75-.34.75h-14q-1 0-.84-.99");
}

.myfbzx5xs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15h18.5v1.25a3 3 0 0 1-3 3H5.75a3 3 0 0 1-3-3Z");
}

.o40hxbbja {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 12.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
