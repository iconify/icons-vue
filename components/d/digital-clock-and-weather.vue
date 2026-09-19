<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="lpu8_8bjy"/><circle class="rwwqqfblf"/><circle class="ylw0d86az"/><path class="gslxkjqmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-clock-and-weather" /></template>
<style>
.gslxkjqmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.347 27.325c.552.463 1.148.675 2.487.675h.312a2 2 0 0 0 2-2h0a2 2 0 0 0-2-1.999m-2.8-3.333c.553-.461 1.15-.672 2.49-.668l.31.002a2 2 0 0 1 2 2h0a2 2 0 0 1-2 1.999m-1.537 0h1.537");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lpu8_8bjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.421 21.089l2-1.089v8m24.152 0v-8l-4.294 5.374h5.3M15.096 22.65a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.081.837-.184 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3");
}

.rwwqqfblf {
  cx: 22.871px;
  cy: 26.65px;
  r: 0.75px;
  fill: currentColor;
}

.ylw0d86az {
  cx: 22.871px;
  cy: 21.35px;
  r: 0.75px;
  fill: currentColor;
}

</style>
