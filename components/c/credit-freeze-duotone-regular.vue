<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo--el8ej"/><path class="g0mb0yldm"/><path class="q9ufcibxz"/><path class="ky4omnbla"/><path class="c1si20bso"/><path class="wihdixnjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:credit-freeze-duotone-regular" /></template>
<style>
.c1si20bso {
  d: path("M10 9v6");
}

.g0mb0yldm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9ufcibxz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wihdixnjz {
  d: path("M14 9v6");
}

.wo--el8ej {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
