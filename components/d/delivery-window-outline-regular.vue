<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="f4f56br_e"/><path class="krhqhqb8m"/><path class="duxnt0uao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delivery-window-outline-regular" /></template>
<style>
.d1zyr9bfc {
  d: path("M12 4v4");
}

.duxnt0uao {
  d: path("M10.5 15h3");
}

.f4f56br_e {
  d: path("M10.5 12H8v6h2.5");
}

.j534ltbcb {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.krhqhqb8m {
  d: path("M13.5 12H16v6h-2.5");
}

.m1mjigbsi {
  d: path("M4 8h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
