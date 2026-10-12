<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><circle class="xrii8hxli"/><path class="ryab5cbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-filter-sharp" /></template>
<style>
.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.ryab5cbdq {
  d: path("M12 7.25a4.75 4.75 0 0 0 0 9.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrii8hxli {
  cx: 12px;
  cy: 12px;
  r: 4.75px;
}

</style>
