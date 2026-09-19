<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwi36wbyv"/><path class="p574-kwgt"/><path class="q8dch4bog"/><circle class="wqbn4n08z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apptester" /></template>
<style>
.p574-kwgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.495 13.352a2.25 2.25 0 0 0-2.283 2.218a2.41 2.41 0 0 0 2.555 2.276c1.26.059 2.063.77 2.063 1.646a1.7 1.7 0 0 1-1.792 1.588");
}

.pwi36wbyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.495 13.352H41.85a1.65 1.65 0 0 1 1.624 1.943l-3.157 17.502a2.19 2.19 0 0 1-2.154 1.804l-23.585.047a2.283 2.283 0 1 1 0-4.567h2.693a2.283 2.283 0 0 0 0-4.566h-4.327a2.219 2.219 0 1 1 0-4.436h6.094");
}

.q8dch4bog {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m24.251 29.766l2.071-11.481h11.116l-2.072 11.48Z");
}

.wqbn4n08z {
  cx: 6.699px;
  cy: 32.448px;
  r: 2.199px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
