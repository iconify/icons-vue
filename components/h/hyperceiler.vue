<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ta1egz63h"/><path class="kz6vqpb8t"/><path class="xv97uoanl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hyperceiler" /></template>
<style>
.kz6vqpb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.048 13.22l13.093-6.116a4.405 4.405 0 0 1 5.86 2.15l6.081 13.114c1.029 2.218.073 4.853-2.135 5.884l-13.092 6.116a4.405 4.405 0 0 1-5.86-2.15L5.914 19.104c-1.03-2.218-.073-4.853 2.134-5.884");
}

.ta1egz63h {
  cx: 37.479px;
  cy: 9.448px;
  r: 2.504px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xv97uoanl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.717 18.681A12.23 12.23 0 0 1 42.5 29.078h0c0 6.755-5.472 12.232-12.223 12.232a12.22 12.22 0 0 1-8.29-3.244");
}

</style>
