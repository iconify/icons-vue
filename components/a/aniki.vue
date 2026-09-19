<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="q3ijh9ban"/><path class="b0aha2brs"/><path class="g5utp55wb"/><ellipse class="zla5w7b4c"/><path class="zo80qabbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aniki" /></template>
<style>
.b0aha2brs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5h-7.171l3.981-17.426m-.031-.006a11.023 11.023 0 1 1 6.411.009");
}

.g5utp55wb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5h7.171l-3.98-17.419l-.001-.007");
}

.q3ijh9ban {
  cx: 24px;
  cy: 15.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.398px;
  ry: 2.905px;
}

.zla5w7b4c {
  cx: 23.966px;
  cy: 15.608px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.126px;
  ry: 6.926px;
}

.zo80qabbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.972 12.966L26.495 9.3m-.405 4.899l3.036-2.322");
}

</style>
