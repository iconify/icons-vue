<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4ytw-bcb"/><ellipse class="f-olpacdp"/><ellipse class="ne0fh7buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fluffy-fall" /></template>
<style>
.f-olpacdp {
  cx: 8.68px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.179px;
  ry: 5.589px;
}

.i4ytw-bcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.741 24.643c.477 2.208 1.685 2.962 3.259 2.962s2.782-.754 3.259-2.962");
}

.ne0fh7buw {
  cx: 39.321px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.179px;
  ry: 5.589px;
}

</style>
