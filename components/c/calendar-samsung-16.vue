<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lj2_ltgfv"/><circle class="nq_6vqa4n"/><path class="nz45sctpe"/></g><path class="kzykk8swa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-samsung-16" /></template>
<style>
.kzykk8swa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-4v1a3.5 3.5 0 1 1-7 0v-1h-8v1a3.5 3.5 0 1 1-7 0v-1h-3a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lj2_ltgfv {
  d: path("m14.28 22.2l4-2.2m0 0v16");
}

.nq_6vqa4n {
  cx: 29.205px;
  cy: 30.667px;
  r: 5.333px;
}

.nz45sctpe {
  d: path("M33.946 21.975C33.156 20.79 31.773 20 29.6 20h-.395a5.31 5.31 0 0 0-5.333 5.333v5.334");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
