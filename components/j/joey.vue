<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6u3vjb8c"/><circle class="n0il_wbaa"/><path class="vx8zuxz6b"/><path class="u99_idb6e"/><circle class="kdo-z4opo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:joey" /></template>
<style>
.kdo-z4opo {
  cx: 31.14px;
  cy: 21.999px;
  r: 2.269px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n0il_wbaa {
  cx: 16.86px;
  cy: 21.999px;
  r: 2.269px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u99_idb6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.092 32.57S27.819 34.397 24 34.397s-5.092-1.827-5.092-1.827M24 30.8a2.783 2.783 0 0 0 3.044-2.796c0-1.218-.498-3.957-3.044-3.957s-3.044 2.74-3.044 3.957A2.783 2.783 0 0 0 24 30.8m7.334-15.819a6.075 6.075 0 0 1 9.326-3.609c-2.297-.055-2.629 1.26-2.629 1.26s6.337-.457 5.369 5.41a1.9 1.9 0 0 0-1.938-.802s3.672 4.9-3.297 5.453");
}

.vx8zuxz6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.718c8.1 0 14.667-4.484 14.667-11.762c0-6.89-6.567-12.702-14.667-12.702S9.333 19.066 9.333 25.956c0 7.278 6.567 11.762 14.667 11.762");
}

.x6u3vjb8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.667 14.981a6.075 6.075 0 0 0-9.327-3.609c2.297-.055 2.629 1.26 2.629 1.26s-6.337-.457-5.369 5.41a1.9 1.9 0 0 1 1.938-.802s-3.672 4.9 3.297 5.452");
}

</style>
