<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="okud9xj_d"/><path class="i7fxd8ole"/><path class="cfgqqu1un"/><path class="ry39d_umh"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keyboard-outline-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.cfgqqu1un {
  d: path("M10.5 10h4");
}

.i7fxd8ole {
  d: path("M5 10h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ry39d_umh {
  d: path("M16 10h4");
}

</style>
