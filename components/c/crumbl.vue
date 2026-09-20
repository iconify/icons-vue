<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w5zq1zbxc"/><path class="wve3yebet"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crumbl" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.w5zq1zbxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.294 22.571v3.069a1.86 1.86 0 1 0 3.72 0v-3.069m0 3.069v1.86m1.821-3.069a1.86 1.86 0 1 1 3.72 0V27.5m-3.72-4.929V27.5");
}

.wve3yebet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.555 24.431a1.86 1.86 0 1 1 3.72 0V27.5m-16.563-3.069a1.86 1.86 0 0 1 1.86-1.86m-1.861 0V27.5m24.063-7v6.07c0 .514.416.93.93.93c.653 0 .943-.621.943-.621m-27.819-.316a1.86 1.86 0 0 1-3.475-.923v-1.209a1.86 1.86 0 0 1 3.473-.926m20.359.926a1.86 1.86 0 1 1 3.72 0v1.209a1.86 1.86 0 1 1-3.72 0m0 1.86v-7");
}

</style>
