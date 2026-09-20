<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k-inlsbxl"/><path class="i3ry39btl"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:le-diplo" /></template>
<style>
.i3ry39btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.513 21.092l-1.106 6.271m11.163-9.466l-1.46 8.283c-.116.653.32 1.183.974 1.183h.355m-12.898-3.905c.23-1.307-.642-2.366-1.95-2.366c-1.306 0-2.552 1.06-2.783 2.366l-.271 1.538c-.23 1.307.642 2.367 1.95 2.367c1.306 0 2.552-1.06 2.783-2.367m-.418 2.367l1.67-9.466m14.208 5.35c.23-1.307 1.477-2.366 2.784-2.366s2.18 1.059 1.95 2.366l-.272 1.538c-.23 1.307-1.477 2.367-2.784 2.367s-2.18-1.06-1.949-2.367zm-10.449 1.749c-.23 1.307.642 2.367 1.95 2.367c1.306 0 2.553-1.06 2.783-2.367l.271-1.538c.23-1.307-.642-2.366-1.949-2.366s-2.553 1.06-2.784 2.366m.418-2.366l-1.669 9.465");
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

.k-inlsbxl {
  cx: 20.024px;
  cy: 18.193px;
  r: 0.75px;
  fill: currentColor;
}

</style>
