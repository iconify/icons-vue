<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_elbtakh"/><path class="rt4fdkb5x"/><path class="u8ileybyr"/><circle class="s3rc965vt"/><path class="znclrhbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instamocks" /></template>
<style>
.a_elbtakh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.268 29.968S9.57 34.85 10.688 43.5h6.488");
}

.rt4fdkb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.824 43.5s3.729-15.958 3.729-19.164S33.956 14.269 24 4.5c-9.956 9.769-10.553 16.63-10.553 19.836S17.176 43.5 17.176 43.5z");
}

.s3rc965vt {
  cx: 24px;
  cy: 38.869px;
  r: 2.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u8ileybyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.732 29.968s4.698 4.882 3.58 13.532h-6.488");
}

.znclrhbad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.196 9.853c1.336.864 2.995 1.363 4.804 1.363s3.468-.5 4.805-1.363");
}

</style>
