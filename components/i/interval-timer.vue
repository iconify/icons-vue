<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9rb99b7m"/><circle class="u3jr84ecy"/><circle class="ou_iwnbwt"/><circle class="j42hh0bkn"/><circle class="f__yhfb0v"/><circle class="gi0uu4b2b"/><path class="ansh-xb6o"/><path class="urxmzpdxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:interval-timer" /></template>
<style>
.ansh-xb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.389 5.266l6.501 6.465l-1.175 5.584M28.31 19.05l3.67 10.827l-4.591 3.196l-.625 9.66");
}

.f__yhfb0v {
  cx: 10.602px;
  cy: 17.608px;
  r: 0.75px;
  fill: currentColor;
}

.gi0uu4b2b {
  cx: 28.259px;
  cy: 14.768px;
  r: 2.017px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j42hh0bkn {
  cx: 16.075px;
  cy: 35.865px;
  r: 0.75px;
  fill: currentColor;
}

.ou_iwnbwt {
  cx: 10.785px;
  cy: 30.612px;
  r: 0.75px;
  fill: currentColor;
}

.u3jr84ecy {
  cx: 16.332px;
  cy: 11.786px;
  r: 0.75px;
  fill: currentColor;
}

.urxmzpdxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43 42.734L36.735 28.13l-4.02-10.816l-4.405 1.736l-5.036 5.94l5.29 1.8m8.171 1.341l-4.755 1.746");
}

.x9rb99b7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.238 35.828v3.526M11.96 24.037H8.435M23.44 42.624a18.44 18.44 0 0 1 0-36.88m-.202 2.939v3.526");
}

</style>
