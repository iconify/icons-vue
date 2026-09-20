<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj6ly32ei"/><path class="ci-m1ibjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gsbank" /></template>
<style>
.ci-m1ibjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.499 8.5a2 2 0 0 0-1.55.736l-11 13.5a2 2 0 0 0 0 2.528l11 13.5a2 2 0 0 0 3.1 0l11-13.5a2 2 0 0 0 0-2.528l-11-13.5A2 2 0 0 0 30.5 8.5m-26 15.545h12.999m13.001 0h12.999");
}

.mj6ly32ei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 8.5a2 2 0 0 0-1.55.736l-11 13.5a2 2 0 0 0 0 2.528l11 13.5a2 2 0 0 0 3.1 0l11-13.5a2 2 0 0 0 0-2.528l-11-13.5A2 2 0 0 0 17.5 8.5");
}

</style>
