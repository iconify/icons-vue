<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vuj67fbmq"/><path class="s8h79jmhr"/><circle class="ce1uc0b5b"/><path class="m4ljzsb_o"/><circle class="qdd6-2b6z"/><path class="pm1urnvss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lidl-connect" /></template>
<style>
.ce1uc0b5b {
  cx: 39px;
  cy: 39px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m4ljzsb_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.278 19.909v8.687h3.794m13.656 0V19.91h1.954a3.8 3.8 0 0 1 3.801 3.8v1.086a3.8 3.8 0 0 1-3.8 3.801Zm-11.544-4.274l4.414-4.414l4.414 4.414l-4.414 4.415zm4.414 4.415l-1.181 1.181m6.777-6.776l-1.182 1.181m-8.828 0l-1.181 1.181");
}

.pm1urnvss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.405 19.909h1.745m-1.745 8.687h.873m16.577 0h.873m-.873-8.687h.873m7.945 0v8.687h3.794M34.8 19.909h1.745M34.8 28.596h.873m5.535 8.124a3.224 3.224 0 1 0 0 4.56");
}

.qdd6-2b6z {
  cx: 20.008px;
  cy: 15.82px;
  r: 2.401px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s8h79jmhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.361 32.643a18.489 18.489 0 1 0-7.762 7.741");
}

.vuj67fbmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 33.525V5.5h-37v37h28.023");
}

</style>
