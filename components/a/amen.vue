<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wp_lbgbzn"/><path class="h4pg2lb3z"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amen" /></template>
<style>
.h4pg2lb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.832 24.692a1.976 1.976 0 1 1 3.953 0v3.26M37 27.953v-3.261a1.976 1.976 0 1 0-3.953 0m0 3.261v-5.238m-1.907 4.24a1.976 1.976 0 0 1-3.693-.979v-1.284a1.976 1.976 0 0 1 3.953 0v.642h-3.953m-12.077 0h-3.502M11 27.952l2.619-7.905l2.618 7.905");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.wp_lbgbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.88 24.692a1.976 1.976 0 1 1 3.953 0v3.26m-3.954-5.237v5.238");
}

</style>
