<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zur9jh-tn"/><path class="p0dcn-oes"/><path class="gf4zuacjp"/><path class="l5hu3qbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forest" /></template>
<style>
.gf4zuacjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.76 25.71c.37-2.42 1.25-3.14 3.49-3.92m-4.68.34c.34-3.81-2.12-11.1-13.94-8.66c4.21 3 1.74 5.94 6.09 8.32a9.9 9.9 0 0 0 7.85.34");
}

.l5hu3qbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.37 22.66c.2-2.95 2-5.53 8.36-4.69c3.83.51 4.2-1.79 4.2-1.79S36.7 24 30.44 24c-4.73 0-5.07-1.34-5.07-1.34");
}

.p0dcn-oes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.3c0-5.53 0-9.8-4.65-11.81");
}

.zur9jh-tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.32a84.5 84.5 0 0 1 37 0V40.5a2 2 0 0 1-2 2h-33a2 2 0 0 1-2-2Z");
}

</style>
