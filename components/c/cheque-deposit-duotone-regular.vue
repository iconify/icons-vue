<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo--el8ej"/><path class="nnux97bry"/><path class="mc5rzvb5h"/><path class="bx5bijb1m"/><path class="ky4omnbla"/><path class="d3f-rpbhx"/><path class="hokxmxb-u"/><path class="xl1fc1yvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cheque-deposit-duotone-regular" /></template>
<style>
.bx5bijb1m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12.5 13 15l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d3f-rpbhx {
  d: path("M5 9h6");
}

.hokxmxb-u {
  d: path("M13 9v6");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.mc5rzvb5h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nnux97bry {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wo--el8ej {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xl1fc1yvu {
  d: path("M10.5 12.5 13 15l2.5 -2.5");
}

</style>
