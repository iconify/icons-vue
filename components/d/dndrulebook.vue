<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o707_xbjc"/><ellipse class="j1-76lb_p"/><circle class="a6r9ykbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dndrulebook" /></template>
<style>
.a6r9ykbin {
  cx: 26.17px;
  cy: 24px;
  r: 4.18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j1-76lb_p {
  cx: 26.16px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9px;
  ry: 4.18px;
}

.o707_xbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.33-2v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
