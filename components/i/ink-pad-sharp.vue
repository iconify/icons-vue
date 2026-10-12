<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="daysyia5e"/><path class="sj7-tib_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ink-pad-sharp" /></template>
<style>
.daysyia5e {
  d: path("m4.22 10.12l1.31-2.49l.47-.88h12l.47.88l1.31 2.49l.47.88H3.75zM2.75 13.5h18.5v7.75H2.75z");
}

.sj7-tib_b {
  d: path("M5.25 16h13.5v2.75H5.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
