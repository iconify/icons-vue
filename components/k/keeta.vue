<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lup-vcbob"/><path class="reg6ngbph"/><path class="i3nvbmb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keeta" /></template>
<style>
.i3nvbmb9h {
  d: path("M14.31 25.54s5.334-1.64 5.334-4.362c0-3.295-5.309-3.518-5.309-.408l-.076 6.533c-.024 2.078 4.572 2.743 5.84-.316m2.689-1.447s5.334-1.64 5.334-4.362c0-3.295-5.31-3.518-5.31-.408l-.075 6.533c-.025 2.078 4.571 2.743 5.839-.316m13.873-4.888s-5.334 1.64-5.334 4.362c0 3.296 5.31 3.519 5.31.409l.075-6.533c.024-2.078-4.572-2.744-5.84.316m-7.226-2.022h5.793m-2.735-4.337v12.741c.024 2.127 2.695 2.018 2.695 2.018");
}

.lup-vcbob {
  d: path("M5.5 14.1v15.946m6.332-12.386c-1.488 2.374-2.25 4.782-6.332 7.037");
}

.reg6ngbph {
  d: path("M8.058 22.932s2.526 11.864 15.303 10.913m7.478-4.135c-.855.879-1.738 1.747-3.038 2.468m-1.336.683c-.48.21-.97.401-1.483.556");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
