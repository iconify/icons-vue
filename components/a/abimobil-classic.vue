<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jl7_qjbts"/><circle class="irj3fgslb"/><path class="i3taowg4y"/><path class="frdqcll6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abimobil-classic" /></template>
<style>
.frdqcll6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.355 30.282l3.723-15.603h-5.903l-3.29 15.939l-4.167-15.939h-5.903l-3.269 14.835");
}

.i3taowg4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.659 35.712v6.308M5.591 5.98l.814 4.35h5.903l-.814-4.35zm2.175 8.699L14.6 42.02h6.214L13.67 14.68zm11.9 22.945l4.1-10.417l1.686 6.426");
}

.irj3fgslb {
  cx: 41.659px;
  cy: 32.797px;
  r: 0.75px;
  fill: currentColor;
}

.jl7_qjbts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.698 38.867h-4.195m-1.04 3.153l3.137-9.521l3.137 9.521m2.593-3.927c0-1.315 1.06-2.38 2.368-2.38h0a2.374 2.374 0 0 1 2.368 2.38v1.547c0 1.315-1.06 2.38-2.368 2.38h0a2.374 2.374 0 0 1-2.367-2.38m0 2.38v-9.521");
}

</style>
