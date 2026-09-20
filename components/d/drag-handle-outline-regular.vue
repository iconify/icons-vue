<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jotdonbiv"/><path class="prj4rnb6x"/><path class="iedujiqkb"/><path class="a-9s6wb0y"/><path class="ccgk_xb3n"/><path class="uesvxd39h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drag-handle-outline-regular" /></template>
<style>
.a-9s6wb0y {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ccgk_xb3n {
  d: path("M7 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.jotdonbiv {
  d: path("M7 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.prj4rnb6x {
  d: path("M15 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uesvxd39h {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
