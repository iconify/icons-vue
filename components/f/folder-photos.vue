<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><path class="px5w6obuk"/><path class="a3rg0rbgp"/><circle class="f-sbprqmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-photos" /></template>
<style>
.a3rg0rbgp {
  d: path("m20.694 28.916l5.078-5.963a2 2 0 0 1 3.045 0l7.63 8.957a1 1 0 0 1-.762 1.648H22.483");
}

.f-sbprqmo {
  cx: 15.12px;
  cy: 21.721px;
  r: 2.279px;
}

.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.px5w6obuk {
  d: path("M22.483 33.558H12.315a1 1 0 0 1-.761-1.648l4.322-5.075a2 2 0 0 1 3.046 0l4.322 5.075a1 1 0 0 1-.76 1.648");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
