<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6bf59bux"/><path class="is-e351zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fxtextedit" /></template>
<style>
.is-e351zn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.53 23h1.3c1.48 0 2.6-.87 3.45-2.52l3.13-6.68c.71-1.5 1.66-2.66 3.51-2.69h1.31M5.3 16.88h9.29M5.72 29l36.84.12M5.72 36.9l36.84.1M30.47 21.29l12.09.12m-12.09-7.77l12.09.12");
}

.p6bf59bux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.56 22.85h1a3.52 3.52 0 0 0 3.47-2.23l3.42-6.91c.85-1.53 1.88-2.55 3.35-2.62h2.7a2.32 2.32 0 0 1 2.54 2.05l1.63 7.39c.55 1.7 1.5 2.24 2.62 2.28h1.23");
}

</style>
