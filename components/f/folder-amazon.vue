<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><g class="y9tr6bcfx"><path class="mp_080bsu"/><path class="ortpsj1kk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-amazon" /></template>
<style>
.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

.mp_080bsu {
  d: path("M28.838 25.472c.917-.371 2.633-.816 3.039-.27c.365.492-.14 2.042-.758 3.128");
}

.ortpsj1kk {
  d: path("M16 25.706c1.158.92 4.579 2.328 8.223 2.328c3.474 0 4.89-.555 7.654-2.831");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
