<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i76lhccuu"/><path class="e8fimk4vt"/><path class="ww81r2wag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exilium" /></template>
<style>
.e8fimk4vt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.72 43.5c-9.626 0-12.175-7.11-9.934-15.926C12.518 41.87 17.72 43.5 17.72 43.5M24 37.98a2.69 2.69 0 1 0 0-5.38V4.5c0 12.74 8.281 25.269 8.281 25.269c2.902-1.7 5.026-3.327 5.875-9.697C37.52 29.91 32.07 42.722 24 43.5zm1.84-9.556H24");
}

.i76lhccuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.98a2.69 2.69 0 1 1 0-5.38V4.5c0 12.74-8.281 25.269-8.281 25.269c-2.902-1.7-5.026-3.327-5.875-9.697C10.48 29.91 15.93 42.722 24 43.5zm-1.84-9.556H24");
}

.ww81r2wag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.28 43.5c9.626 0 12.175-7.11 9.934-15.926C35.482 41.87 30.28 43.5 30.28 43.5");
}

</style>
