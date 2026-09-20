<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="ik7am9bxi"/><rect class="c5mogdb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:280blocker" /></template>
<style>
.c5mogdb1g {
  width: 6.625px;
  height: 10px;
  x: 30.033px;
  y: 19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.313px;
  ry: 3.313px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ik7am9bxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.342 22.313a3.316 3.316 0 0 1 3.97-3.25c1.389.267 2.498 1.469 2.636 2.876c.103 1.048-.228 2.081-.952 2.716C15.657 25.83 11.343 29 11.343 29h6.625m5.202-5a2.5 2.5 0 0 0 0 5h1.624a2.5 2.5 0 0 0 0-5m0 0a2.5 2.5 0 0 0 0-5H23.17a2.5 2.5 0 0 0 0 5m-.001 0h1.625");
}

</style>
