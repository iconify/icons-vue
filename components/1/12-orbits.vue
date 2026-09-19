<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="pl708vb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:12-orbits" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.pl708vb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.274 20.466l2.428-1.321v9.71m2.365-6.494a3.22 3.22 0 0 1 3.855-3.155c1.349.26 2.426 1.426 2.56 2.793c.1 1.017-.222 2.02-.924 2.637c-1.302 1.142-5.491 4.22-5.491 4.22H37.5m-27-6.495a3.22 3.22 0 0 1 3.855-3.155c1.349.26 2.426 1.426 2.56 2.793c.1 1.017-.221 2.02-.924 2.637c-1.301 1.142-5.491 4.22-5.491 4.22h6.433M19.454 24h6.023");
}

</style>
