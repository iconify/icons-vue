<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="re--udz7m"/><circle class="fms4_l2rd"/><circle class="tqqi5dimq"/><circle class="hi--c4b6f"/><circle class="j1hh3tb3h"/><circle class="e_36zmb5j"/><circle class="xaz706b0a"/><path class="qhc-to0qd"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:graphene-os" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e_36zmb5j {
  cx: 13.669px;
  cy: 29.965px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fms4_l2rd {
  cx: 24px;
  cy: 12.071px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hi--c4b6f {
  cx: 34.331px;
  cy: 29.965px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j1hh3tb3h {
  cx: 34.331px;
  cy: 18.035px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qhc-to0qd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.91V2.5m0 43v-7.41m12.202-21.135l6.418-3.705M5.38 34.75l6.418-3.705m24.404 0l6.418 3.705M5.38 13.25l6.418 3.705");
}

.re--udz7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.458 16.956l-6.589-3.804m6.589 17.895l-6.589 3.804m-12.202-7.046v-7.607m8.46 14.653l-6.589-3.804m18.79-3.242v-7.607m-12.201-7.046l-6.589 3.804");
}

.tqqi5dimq {
  cx: 24px;
  cy: 35.929px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xaz706b0a {
  cx: 13.669px;
  cy: 18.035px;
  r: 2.161px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
