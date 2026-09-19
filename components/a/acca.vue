<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lg3h297ok"/><path class="erlf059ua"/><path class="gxk3-wbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acca" /></template>
<style>
.erlf059ua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.75 30.62l2.24-3.98l-3.98.34L24.25 23");
}

.gxk3-wbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.89 4.5h10.22a2.28 2.28 0 0 1 2.29 2.29v1.46h2.54A3 3 0 0 1 37 11.31v29.14a3 3 0 0 1-3.05 3H14.06a3 3 0 0 1-3.05-3V11.31a3 3 0 0 1 3.05-3.06h2.54V6.79a2.28 2.28 0 0 1 2.29-2.29");
}

.lg3h297ok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.8a2.2 2.2 0 0 0-.87.18l-5.81 2.38a.85.85 0 0 0-.52.78v5.12c0 4.58 5.18 7.55 7.2 7.55s7.2-3 7.2-7.55v-5.12a.85.85 0 0 0-.52-.78L24.87 19a2.2 2.2 0 0 0-.87-.2");
}

</style>
