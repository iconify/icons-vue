<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="wowt3pbed"/><circle class="n-p8fib3p"/><path class="flrmejs6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:key-driver" /></template>
<style>
.flrmejs6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.441 34.535H29.56v7.306A1.66 1.66 0 0 1 27.9 43.5h-7.8a1.66 1.66 0 0 1-1.659-1.659zm1.995 0V43.5m2.404-8.965v6.679m4.724-6.679V43.5m-2.404-8.965v6.679");
}

.n-p8fib3p {
  cx: 24px;
  cy: 21.265px;
  r: 4.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wowt3pbed {
  width: 18.424px;
  height: 30.035px;
  x: 14.788px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.645px;
  ry: 2.645px;
}

</style>
