<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="f_qnzabbp"/><path class="ehgq2cbyc"/><path class="kuj3y19sd"/><path class="ky4omnbla"/><path class="d3f-rpbhx"/><path class="hokxmxb-u"/><path class="xl1fc1yvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cheque-deposit-duotone-thin" /></template>
<style>
.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d3f-rpbhx {
  d: path("M5 9h6");
}

.ehgq2cbyc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f_qnzabbp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hokxmxb-u {
  d: path("M13 9v6");
}

.kuj3y19sd {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 12.5 13 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.xl1fc1yvu {
  d: path("M10.5 12.5 13 15l2.5 -2.5");
}

</style>
