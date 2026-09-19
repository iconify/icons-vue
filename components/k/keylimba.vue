<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><ellipse class="karentfnc"/><ellipse class="ab-ywxbuf"/><path class="nmcb4-b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keylimba" /></template>
<style>
.ab-ywxbuf {
  cx: 31.577px;
  cy: 20.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.423px;
  ry: 2.692px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.karentfnc {
  cx: 16.423px;
  cy: 20.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.423px;
  ry: 2.692px;
}

.nmcb4-b8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.671 27.46c-1.328 1.84-3.335 3.08-6.671 3.08s-5.343-1.238-6.671-3.08");
}

</style>
